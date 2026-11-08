# 🧩 Meus Projetos n8n

Automações e agentes de inteligência artificial com **n8n** — de um agente conversacional a um agente que apoia decisões de negócio.

Este repositório reúne meus projetos com n8n, cada um em sua própria pasta, com documentação, prints e o workflow exportado (`.json`) pronto para importar.

## 📂 Projetos

| Projeto | Descrição | Tecnologias |
|---|---|---|
| [`chat-basico/`](./chat-basico) | Agente de IA via chat web, com memória de conversa e ferramentas de cálculo e pesquisa | n8n · Groq · Google Sheets · Calculator · Wikipedia |
| [`assistente-whatsapp-estudos/`](./assistente-whatsapp-estudos) | Assistente de estudos integrado ao WhatsApp (Z-API), com comando `/quiz` e busca na web | n8n · Groq · WhatsApp (Z-API) · SerpApi · Google Sheets |
| [`agente-analise-reembolso/`](./agente-analise-reembolso) | Agente de IA para automatizar análise e resposta de solicitações de reembolso, classificando clientes e notificando a equipe | n8n · Google Gemini · Google Sheets · Gmail · Telegram |

## 🧠 Sobre a evolução dos projetos

Os projetos seguem uma ordem crescente de complexidade. O **Agente de Chat** estabelece a estrutura fundamental de um AI Agent no n8n (Model, Memory, Tools). O **Assistente via WhatsApp** partiu dessa base e adicionou uma camada real de uso prático: integração com uma API externa de mensageria, lógica condicional para comandos personalizados, e mais ferramentas de busca. O **Agente de Análise de Reembolso** dá um passo além: aplica IA a um processo real de decisão de negócio, combinando classificação de dados, múltiplos canais de resposta (e-mail e Telegram) e regras de negócio sensíveis.

## 🛠️ Tecnologias em comum

`n8n` · `LLMs (Groq, Google Gemini)` · `Google Sheets` · `LangChain Tools`

## 🚀 Como usar os projetos

Cada pasta é independente e contém seu próprio `README.md` com instruções específicas. De forma geral:

1. Entre na pasta do projeto desejado
2. Importe o `workflow.json` no seu n8n (**Menu → Import from File**)
3. Configure suas próprias credenciais (indicadas no README de cada projeto)
4. Ative o workflow para testar

## 🎓 Certificado

### Imersão Agentes IA — Hashtag Treinamentos

Certificado de conclusão da **Imersão Agentes IA** (8 horas), emitido pela **Hashtag Treinamentos** em 23/07/2026.

![Certificado Imersão Agentes IA](./certificados/certificado-imersao-agentes-ia.png)

---

*Desenvolvido por **Amanda Carolina** · [LinkedIn](https://www.linkedin.com/in/amanda-carolina-bs)*
