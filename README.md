# UM TOQUE A MAIS

Projeto completo de loja virtual com painel administrativo.

## Recursos
- Loja virtual de roupas
- Página de produto
- Carrinho persistente no navegador
- Checkout com cadastro de clientes
- Painel administrativo com login
- Cadastro e exclusão de produtos
- Cadastro e exclusão de categorias
- Configurações do site
- Visualização de clientes cadastrados
- Prisma + PostgreSQL

## Como rodar
1. Copie `.env.example` para `.env`
2. Preencha `DATABASE_URL`, `NEXTAUTH_SECRET` e `NEXTAUTH_URL`
3. Rode:

```bash
npm install
npx prisma generate
npx prisma migrate dev --name init
npm run create-admin
npm run dev
```

## Login padrão
- E-mail: `admin@umtoqueamais.com`
- Senha: `123456`

## Observações
- O projeto foi preparado para GitHub Codespaces + Neon.
- Para subir no GitHub, envie toda a pasta do projeto.
