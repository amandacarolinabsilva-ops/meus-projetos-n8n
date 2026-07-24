# 🧩 Meus Projetos n8n

Estudos e práticas com **n8n** — automações e agentes de inteligência artificial, do básico ao avançado.

Este repositório reúne meus projetos de aprendizado com n8n, cada um em sua própria pasta, com documentação, prints e o workflow exportado (`.json`) pronto para importar.

## 📂 Projetos

| Projeto | Descrição | Tecnologias |
|---|---|---|
| [`chat-basico/`](./chat-basico) | Meu primeiro agente de IA, via chat web, com memória de conversa e ferramentas de cálculo/pesquisa | n8n · Groq · Google Sheets · Calculator · Wikipedia |
| [`assistente-whatsapp-estudos/`](./assistente-whatsapp-estudos) | Evolução do primeiro projeto: assistente de estudos real, integrado ao WhatsApp, com comando `/quiz` e busca na web | n8n · Groq · WhatsApp (Z-API) · SerpApi · Google Sheets |
| [`agente-analise-reembolso/`](./agente-analise-reembolso) | Agente de IA para automatizar análise e resposta de solicitações de reembolso, classificando clientes e notificando a equipe | n8n · Google Gemini · Google Sheets · Gmail · Telegram |

## 🧠 Sobre a evolução dos projetos

Os projetos estão organizados em ordem cronológica de aprendizado. O **Chat Básico** foi o ponto de partida — focado em entender a estrutura fundamental de um AI Agent no n8n (Model, Memory, Tools). O **Assistente via WhatsApp** partiu dessa base e adicionou uma camada real de uso prático: integração com uma API externa de mensageria, lógica condicional para comandos personalizados, e mais ferramentas de busca. O **Agente de Análise de Reembolso** dá um passo além: aplica IA a um processo real de decisão de negócio, combinando classificação de dados, múltiplos canais de resposta (e-mail e Telegram) e regras de negócio sensíveis.

## 🛠️ Tecnologias em comum

`n8n` · `LLMs (Groq, Google Gemini)` · `Google Sheets` · `LangChain Tools`

## 🚀 Como usar os projetos

Cada pasta é independente e contém seu próprio `README.md` com instruções específicas. De forma geral:

1. Entre na pasta do projeto desejado
2. Importe o `workflow.json` no seu n8n (**Menu → Import from File**)
3. Configure suas próprias credenciais (indicadas no README de cada projeto)
4. Ative o workflow para testar

---

*Repositório de estudos práticos com n8n e automação de IA.*
