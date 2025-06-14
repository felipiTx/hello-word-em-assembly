; hello.asm - Exibe "Hello, World!" em uma MessageBox no Windows
.386
.model flat, stdcall
option casemap:none

include windows.inc
include user32.inc
include kernel32.inc

includelib user32.lib
includelib kernel32.lib

.data
    mensagem db "Hello, World!", 0
    titulo   db "Mensagem", 0

.code
start:
    push 0              ; MB_OK
    push offset titulo  ; título da janela
    push offset mensagem; texto da mensagem
    push 0              ; hWnd
    call MessageBoxA

    push 0              ; código de saída
    call ExitProcess

end start
