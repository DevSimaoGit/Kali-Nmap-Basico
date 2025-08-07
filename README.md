# 🔍 Guia de Varredura com Nmap no Kali Linux

Este repositório contém um passo a passo completo para realizar varreduras com o **Nmap** usando o **Kali Linux**, voltado para iniciantes em cibersegurança, bug bounty e pentest.

---

## 🛠️ Requisitos

- Kali Linux instalado (VM, WSL ou nativo)
- Terminal com permissões root ou sudo
- Alvo para escaneamento (ex: máquina local, VM, lab Hack The Box, TryHackMe, etc.)

---

## 📖 Índice

1. [Preparar o ambiente](#preparar-o-ambiente)  
2. [Identificar o alvo](#identificar-o-alvo)  
3. [Fazer o primeiro scan](#fazer-o-primeiro-scan)  
4. [Scan de portas](#scan-de-portas)  
5. [Detectar serviços e versões](#detectar-serviços-e-versões)  
6. [Scan agressivo](#scan-agressivo)  
7. [Salvar resultado](#salvar-resultado)  
8. [Recapitulando comandos](#recapitulando-comandos)  

---

## Preparar o ambiente

### 1.1 Abrir o terminal no Kali Linux
- Atalho: `Ctrl + Alt + T`
- Ou clique no ícone do terminal.

### 1.2 Verificar se o Nmap está instalado

```bash
nmap --version

Se não estiver, instale:

Copiar
Editar
sudo apt update && sudo apt install nmap -y
