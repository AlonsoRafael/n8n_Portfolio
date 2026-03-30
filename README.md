# n8n Portfolio - Chatbot de Perfil

Template de automacao no n8n para chatbot de portfolio profissional.

## O que este projeto faz

- Recebe mensagem por webhook.
- Usa um AI Agent com memoria simples.
- Consulta dados em Supabase (tecnologias, projetos e experiencias).
- Responde de forma pronta para uso em frontend ou integracao.

## Arquivo principal

- portfolio.json

## Como usar

1. Abra o n8n.
2. Importe o arquivo portfolio.json.
3. Configure as credenciais dos nodes.
4. Ative o workflow.

## Campos que precisam ser trocados

No arquivo estao placeholders para manter seguranca em repositorio publico. Troque pelos valores reais no seu ambiente:

- REPLACE_WITH_WEBHOOK_ID
- REPLACE_WITH_GOOGLE_GEMINI_CREDENTIAL_ID
- REPLACE_WITH_GOOGLE_GEMINI_CREDENTIAL_NAME
- REPLACE_WITH_SUPABASE_CREDENTIAL_ID
- REPLACE_WITH_SUPABASE_CREDENTIAL_NAME
- REPLACE_WITH_INSTANCE_ID
