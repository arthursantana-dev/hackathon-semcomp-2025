# Agente Financeiro para Telegram BTG
## Nome da equipe: 93
## Participantes
- Arthur Alexandre Santos Santana  
- Arthur Martins Pereira  
- Christyan Paniago Nantes  
- Giovanna Nascimento Noventa  

---

## Funcionalidades - Agentes
### Orquestrador
Delega as funções entre os devidos agentes, assim como recebe as entradas e saídas.
![Workflow do orquestrador central](Orquestrador.png)
### Buy/Sell
Permite a compra e venda de ativos de forma rápida.
![Workflow do Buy-Sell](Buy-Sell.png)
### Notícias
Busca as notícias do Research do BTG Pactual mais relevantes para o portfólio do usuário.
![Workflow do Notícia](News%20Workflow.png)
### Resumo de notícias
Permite a síntese das notícias do Research do BTG Pactual: busca a notícia completa através de um link e resume-a.
![Workflow do Resumo de Notícias](Summarizer%20de%20Notícia.png)
### Analisar carteira
Busca os ativos do portfólio do usuário e analisa como aqueles ativos estão se comportando com o tempo.
![Workflow de Análise de carteira](Avaliar%20Carteira.png)
### Conversacional
Gera recomendações de investimento e gerencia conversas gerais.
![Workflow do Conversacional](Conversacional.png)

---

## Features
- Sistema de entrada multimodal, com entradas de vídeo, texto e imagem
- Integração com o Telegram
- Integração com o Google Gemini
- Integração com banco de dados PostgreSQL (Supabase) para contexto e dados de usuários, notícias e ativos.
