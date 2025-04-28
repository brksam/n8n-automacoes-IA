# Projetos de Automação com n8n

Este repositório contém dois projetos usando n8n para automação com inteligência artificial:

## Projetos

### 1. Chat IA com Wikipedia e Calculadora
- Usuário acessa um link e conversa com uma IA.
- Integração com Wikipedia e funções de calculadora.
- Fluxo salvo em `workflows/chat-ia-wikipedia.json`.

### 2. IA no WhatsApp
- IA integrada ao WhatsApp para respostas automáticas.
- Integrações com Google Sheets para registrar as mensagens.
- Fluxo salvo em `workflows/ia-whatsapp.json`.

## Tecnologias usadas
- n8n
- Groq Chat Model (IA)
- Wikipedia API
- Calculadora (n8n Internal Tool)
- WhatsApp API (via HTTP Request)
- Google Sheets

## Como usar
1. Instale o n8n localmente ou use o n8n cloud.
2. Importe o arquivo `.json` correspondente.
3. Configure as credenciais para Groq, WhatsApp, Google Sheets.
4. Execute o workflow!

## Screenshots
![Chat IA](./imagens/460de42a-b88d-456b-8773-a4cd9b017127.png)
![WhatsApp IA](./imagens/9ae24400-47db-47b0-b163-3709cbaf9e64.png)

---
