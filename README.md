<h1 align="center">🌐 Roteamento Estático usando CLI ⚙️</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Pendente-yellow.svg" alt="Status do Projeto">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="Licença MIT">
  </a>
</p>

<p align="center">
  Projeto prático desenvolvido para simular e configurar <strong>roteamento estático</strong> entre redes distintas usando o <strong>Cisco Packet Tracer</strong>, conectando os campi de <strong>Campina Grande</strong> e <strong>João Pessoa</strong> com uma conexão de longa distância.
</p>

<p align="center">
  <strong>📡 Roteamento entre redes, DHCP, DNS, Servidor Web e configuração completa via CLI!</strong>
</p>

---

## 🧠 Objetivo do Projeto

Este projeto tem como foco aplicar conhecimentos fundamentais sobre **roteamento estático**, **endereçamento IP**, e **serviços de rede** em um cenário simulado, usando a interface de linha de comando (CLI) dos roteadores Cisco.

---

## 🗽 Cenário e Topologia

A topologia contempla os seguintes dispositivos:

- 💻 4 PCs
- 🌐 1 Servidor
- 🛠️ 1 Switch 2950-24
- 🧷 1 Roteador 2621XM

A topologia conecta duas redes distintas (representando os campi) utilizando **roteamento estático** para permitir a comunicação entre elas.

---

## 🚀 Funcionalidades Implementadas

### 🔌 Configuração de Endereçamento IP

- Endereços IPv4 atribuídos manualmente aos PCs e ao Servidor.
- Testes de conectividade via `ping`.

---

### 🔄 DHCP

- Transição de IPs estáticos para dinâmicos usando servidor DHCP.
- Configuração de pools separados para os dispositivos da rede.

---

### 🌐 Servidor Web

- Configuração de servidor com páginas HTML acessíveis via navegador dos PCs.
- Testes de acesso à aplicação web hospedada localmente.

---

### 🧱 DNS

- Configuração de servidor DNS para resolução de nomes.
- Acesso ao servidor web via nome de domínio (e não apenas IP).

---

### 🛀 Roteamento Estático via CLI

- Configuração completa utilizando o **modo de configuração global** e **interface**.
- Criação de rotas estáticas para interligar as redes dos dois campi.
- Verificação de conectividade usando comandos como `ping` e `traceroute`.

---

## 🚨 Desafio Ativo

Durante os testes, foi identificado um problema de conectividade entre um PC e o servidor. A comunicação via ping falha, e está sendo investigada como parte do processo de aprendizado e depuração de rede.

---

## 📂 Arquivos Disponíveis

| Tipo | Arquivo | Descrição |
|------|---------|-----------|
| 📦 Cenário Packet Tracer | [RoteamentoEstatico.pkt](https://academicoifpbedubr-my.sharepoint.com/:u:/g/personal/joseffer_maxwel_academico_ifpb_edu_br/EU0HEiyu9cNHugIqUe5MzlgB5USJ3dv2gfp6mvpAwtKc8g?e=BPwHpX) | Arquivo de topologia com todas as configurações aplicadas |
| 📄 Documentação | [Instruções.pdf](https://academicoifpbedubr-my.sharepoint.com/:b:/g/personal/joseffer_maxwel_academico_ifpb_edu_br/EeCAutS-rbpJidMdLpGC0HwBj7tSCgqE0s4_8p-Hl25dIw?e=nJ01E9) | Etapas detalhadas de configuração e testes realizados |

---

## 💻 Requisitos

- [Cisco Packet Tracer](https://www.netacad.com/)

> ⚠️ **Nota:** É necessário ter uma conta gratuita na Cisco Networking Academy para baixar e usar o simulador.

---

## 🛠️ Tecnologias Utilizadas

- Cisco Packet Tracer
- Roteamento Estático via CLI
- DHCP
- DNS
- Servidor Web Local

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas!  
Se quiser sugerir melhorias, relatar problemas ou compartilhar ideias, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

---

## 📜 Licença

Distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais informações.

---

## 📬 Contato

📧 Email: [joseffermax1472@gmail.com](mailto:joseffermax1472@gmail.com)  
🔗 GitHub: [@joseffermax](https://github.com/joseffermax)

---

<h2 align="center">🧠 Explore, configure e domine o roteamento estático! 🚀</h2>
