# Minhas Finanças

App pessoal (PWA) de receitas, despesas e dízimo automático. Funciona offline e sincroniza com o Supabase.

## 1. Supabase
1. Crie um projeto em supabase.com.
2. Abra **SQL Editor**, cole o arquivo `schema.sql` e clique em **Run**.
3. Em **Project Settings › API**, copie a **Project URL** e a **anon public key**.
4. Depois de criar sua conta pelo app: **Authentication › Sign In / Providers** › desligue **Allow new users to sign up** (ninguém mais cria conta).

## 2. GitHub Pages
1. Envie todos os arquivos desta pasta para um repositório.
2. Abra **Settings › Pages › Branch: main / root** e salve.
3. Acesse `https://SEU-USUARIO.github.io/SEU-REPO/`.

## 3. No app
**Ajustes › Nuvem**: cole a URL e a anon key › **Criar conta** › **Entrar**.
No celular: menu do navegador › **Adicionar à tela inicial**.

> A anon key é pública por design. A segurança vem do login e do RLS (`schema.sql`).
