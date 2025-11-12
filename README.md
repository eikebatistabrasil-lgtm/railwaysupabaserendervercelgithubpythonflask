# 🧠 Admin Total - Sistema de Mensagens

Gerencie completamente sua tabela de mensagens no Supabase através de um painel web.

## 🚀 Stack
- Frontend: HTML + JavaScript (Supabase JS SDK)
- Backend: Supabase (PostgreSQL + API REST)
- Deploy: Vercel
- Versionamento: GitHub

## 🗃️ Banco de Dados
Tabela principal: `messages`
| Coluna | Tipo | Descrição |
|---------|-------|------------|
| id | bigint | Chave primária |
| username | text | Nome do usuário |
| message | text | Mensagem enviada |
| created_at | timestamptz | Data de criação automática |

## ⚙️ Configuração
1. Configure suas variáveis no Supabase:
   - URL do projeto
   - Anon Key pública
2. Edite o arquivo `index.html` e insira:
   ```js
   const SUPABASE_URL = "https://SEU_URL.supabase.co";
   const SUPABASE_KEY = "SUA_ANON_KEY";
