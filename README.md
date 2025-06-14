# hello world em assembly 

# 💬 Hello World em Assembly para Windows

Este é um programa simples em Assembly que exibe "Hello, World!" em uma MessageBox no Windows.

## 🧰 Requisitos

- Windows 32 ou 64 bits
- [MASM32 SDK](https://www.masm32.com/) instalado
  
## 📥 Como compilar
Abra o **"MASM32 SDK Command Prompt"** e digite os comandos abaixo:
```bash
ml /c /coff hello.asm
link /subsystem:windows hello.obj

