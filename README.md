# kali-nmap-basico

# 🔍 Guia de Varredura com Nmap no Kali Linux

Este repositório contém um passo a passo completo para realizar varreduras com o **Nmap** usando o **Kali Linux**, voltado para iniciantes em cibersegurança, bug bounty e pentest.

---

## 🛠️ Requisitos

- Kali Linux instalado (VM, WSL ou nativo)
- Terminal com permissões root ou sudo
- Alvo para escaneamento (ex: máquina local, VM, lab Hack The Box, TryHackMe, etc.)

---

## 📖 Índice

1. [Introdução ao Nmap](#introdução-ao-nmap)
2. [Tipos de Varredura](#tipos-de-varredura)
   - [Scan Simples (Ping Scan)](#1-scan-simples-ping-scan)
   - [Scan de Portas](#2-scan-de-portas)
   - [Scan de Versão](#3-scan-de-versão)
   - [Scan Agressivo](#4-scan-agressivo)
3. [Exportando Resultados](#exportando-resultados)
4. [Casos de Uso em Pentest](#casos-de-uso-em-pentest)
5. [Referências](#referências)

---

## Introdução ao Nmap

O Nmap (Network Mapper) é uma ferramenta de código aberto para varredura de redes e auditoria de segurança. Ele permite identificar hosts, serviços e sistemas operacionais em uma rede.

---

## Tipos de Varredura

### 1. Scan Simples (Ping Scan)

```bash
nmap -sn 192.168.0.0/24
