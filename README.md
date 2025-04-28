# Projetos de Automação com n8n — Protótipos de Bots com IA

Este repositório contém dois projetos simples desenvolvidos usando **n8n** para automação com inteligência artificial, integração com Wikipedia, calculadora e WhatsApp.

⚠️ **Atenção:** Estes projetos são apenas **protótipos básicos** de bots. Não estão totalmente integrados nem finalizados para uso em produção.

## Projetos

### 1. Chat IA com Wikipedia e Calculadora
- Um link onde o usuário pode conversar com uma IA simples.
- A IA pode buscar informações na Wikipedia e realizar cálculos.
- Todas as mensagens enviadas pelo usuário são registradas automaticamente em uma planilha do Google Sheets para documentação e análise.
- Fluxo salvo em `workflows/chat-ia-wikipedia.json`.

### 2. IA no WhatsApp
- IA integrada de forma básica ao WhatsApp para responder mensagens automaticamente.
- A IA também tem acesso à Wikipedia e à calculadora conforme necessário.
- Todas as mensagens trocadas são registradas em uma planilha no Google Sheets.
- Fluxo salvo em `workflows/ia-whatsapp.json`.

## Tecnologias usadas
- n8n
- Groq Chat Model (IA)
- Wikipedia API
- Calculadora (n8n Internal Tool)
- WhatsApp API (via HTTP Request)
- Google Sheets

## Como usar
1. Instale o n8n localmente ou utilize o n8n cloud.
2. Importe os arquivos `.json` localizados na pasta `workflows/`.
3. Configure as credenciais necessárias:
   - API do Groq ou outro modelo de IA.
   - Integração com Google Sheets.
   - API de envio/recebimento de mensagens WhatsApp.
4. Execute os workflows.
5. As mensagens serão documentadas automaticamente nas planilhas Google Sheets.

## Observações importantes
- Estes projetos são protótipos e servem apenas para estudo e testes.
- Não possuem validações de segurança, controle de erros ou integrações completas.
- Ajustes são necessários para um uso real em ambientes de produção.

## Screenshots
![Chat IA](./imagens/460de42a-b88d-456b-8773-a4cd9b017127.png)
![WhatsApp IA](./imagens/9ae24400-47db-47b0-b163-3709cbaf9e64.png)

---
