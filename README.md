
<h1 align="center">
  <img src="https://img.shields.io/static/v1?label=BIGDATA%20POR&message=MAYCON%20BATESTIN&color=0e76a8&style=flat-square&logo=linkedin"/>
</h1>

<h2 align="center">📊 Agente Especializado em Conteúdos para o Linkedin Utilizando N8N</h2>

---

## 🎯 Propósito

Este workflow automatiza a criação e publicação de conteúdo educacional no LinkedIn com foco em temas do universo de dados. Ele integra ferramentas de inteligência artificial, planilhas do Google e agendamento de tarefas para transformar entradas simples em posts dinâmicos e atrativos.

---

## ⚙️ Funcionalidades

- 🔄 Executa diariamente em horários agendados
- 📑 Lê termos e conceitos de uma planilha no Google Sheets
- 🤖 Gera textos envolventes com IA (LLaMA 3 via Groq)
- 🧠 Mantém memória de sessão para consistência narrativa
- 🔍 Busca complementos via Google com SerpAPI
- 💬 Publica automaticamente no LinkedIn
- 📚 Integra-se a uma série educacional chamada “Dicionário de Dados”

---

## 🧩 Componentes Principais

- `Schedule Trigger`: Define os horários diários de execução
- `Google Sheets`: Lê os dados e remove entradas processadas
- `Limit`: Controla a quantidade de dados tratados por execução
- `AI Agent`: Cria o post com base em prompt customizado
- `Groq Chat Model`: Fornece o modelo de linguagem (LLaMA 3)
- `Simple Memory`: Mantém histórico e contexto das execuções
- `SerpAPI`: Reforça o conteúdo com dados públicos de busca
- `LinkedIn`: Publica automaticamente os posts

---

## 🔐 Requisitos de Credenciais

- Conta do **Google Sheets** com permissão de leitura e edição
- Chave de API do **Groq** para acesso ao LLaMA 3
- Chave de API do **SerpAPI**
- Conta **LinkedIn** autorizada para publicações automáticas

---

 

## ▶️ Como Usar

1. Instale e configure o [N8N](https://n8n.io) no seu ambiente local ou nuvem.
2. Importe o arquivo `My_workflow.json` no editor do N8N.
3. Configure as credenciais necessárias:
   - Conta do LinkedIn
   - Conta Google com acesso à planilha
   - Chaves do Groq e SerpAPI
4. Ative o workflow.
5. Os posts serão publicados automaticamente de forma diária.

---

## 👨‍💻 Autor

Desenvolvido por **Maycon Batestin** — apaixonado por IA, automações e conteúdo educacional para a comunidade de dados.

---

## 🧠 Inspiração

Este projeto nasceu da vontade de democratizar o conhecimento em ciência de dados com linguagem simples, direta e divertida. 🚀

---
