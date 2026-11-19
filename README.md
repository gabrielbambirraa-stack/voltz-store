# VOLTZ STORE

Loja fictícia de tecnologia e acessórios, criada com **React + Vite + CSS** para fins de demonstração.

## Como rodar

```bash
npm install
npm run dev
```

Abra o endereço exibido no terminal (normalmente http://localhost:5173).

## Build de produção

```bash
npm run build
npm run preview
```

## Funcionalidades

- Header fixo com menu responsivo, pesquisa em tela cheia e carrinho
- Banner principal, categorias com imagens e 10 produtos
- Busca, filtro por categoria e ordenação por preço
- Carrinho com adicionar, remover, alterar quantidade, total automático e persistência no `localStorage`
- Feedback visual (botão, contador do carrinho e toast) ao adicionar produtos
- Seções Sobre, Newsletter (com validação de e-mail) e Footer
- Animações suaves de entrada e layout totalmente responsivo

## Estrutura

```
src/
  components/   Header, Hero, Categories, Products, ProductCard, CartDrawer, ...
  data/         products.js (produtos, categorias e imagens)
  hooks/        useCart.js (lógica do carrinho)
  styles/       index.css
  utils/        helpers.js
```

## Imagens

As imagens vêm do Unsplash por URL. Para trocar, edite `src/data/products.js`.
Se uma imagem não carregar, um placeholder da marca é exibido automaticamente.

> Todos os dados (produtos, preços, contatos e redes sociais) são fictícios.
