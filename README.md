# afroshop# afroshop

Esta plataforma é um marketplace Africano, para fornecedores e qualquer pessoa se cadastrar, é grátis. Compre em grupo e pague menos, ou venda produtos e receba seu pagamento ou comissão. 

## Como rodar localmente

Requisitos:
- Node.js 16+ (ou a versão usada no projeto)
- Yarn ou npm

Passos básicos:

1. Instalar dependências:

```bash
yarn install
# ou
npm install
```

2. Criar um arquivo `.env` na raiz com as variáveis necessárias (ex.: `PORT`, `MONGO_URL`, `STRIPE_KEY`). Nunca comitar `.env`.

3. Rodar em modo de desenvolvimento:

```bash
yarn dev
# ou
npm run dev
```

4. Testar endpoints com Postman / Insomnia ou via frontend apontando para `http://localhost:PORT`.

Observações:
- `node_modules/` está no `.gitignore` e não deve ser versionado.
- Se precisar limpar dependências e reinstalar, remova `node_modules/` localmente e rode `yarn install`.

Contribuições são bem-vindas. Abra issues ou PRs com melhorias.
