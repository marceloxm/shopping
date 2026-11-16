# 🛒 E-commerce Shopping (React + Redux)

## 📖 Sobre o Projeto

Este projeto é uma aplicação web de **E-commerce (Shopping)** desenvolvida com **React** e **Redux**, criada como parte de um desafio prático de bootcamp da **[Digital Innovation One (DIO)](https://dio.me)**.

O objetivo principal da aplicação é demonstrar o gerenciamento centralizado de estado em uma loja virtual utilizando **Redux** (controle de produtos, carrinho de compras, quantidades e valores totais), além de explorar a combinação de duas das principais bibliotecas de estilização do ecossistema front-end: **Material UI** e **Bootstrap**.

---

## ✨ Funcionalidades

- **Vitrine de Produtos:** Listagem dinâmica de itens disponíveis para compra com imagem, nome, categoria e preço.
- **Filtragem por Categoria:** Navegação rápida para filtrar os produtos exibidos de acordo com suas categorias (ex.: seleções nacionais, clubes europeus, históricos, etc., dependendo do catálogo cadastrado).
- **Carrinho de Compras Interativo (Redux):**
  - Adicionar produtos ao carrinho;
  - Aumentar ou diminuir a quantidade de cada item;
  - Remover produtos individualmente do carrinho;
  - Cálculo automático da quantidade total de itens e do valor final da compra;
  - Contador dinâmico atualizado em tempo real no ícone do carrinho no cabeçalho.
- **Navegação entre Páginas:** Alternância fluida entre a página inicial da loja e a página de contato/formulário (via React Router).

---

## 🛠️ Tecnologias Utilizadas

Com base na estrutura e descrição do repositório (`package.json` e `yarn.lock`), o projeto utiliza as seguintes tecnologias:

- **[React](https://react.dev):** Biblioteca JavaScript para construção da interface baseada em componentes.
- **[Redux](https://js.org) & React-Redux:** Gerenciamento previsível e global do estado da aplicação (carrinho e lista de produtos).
- **[Material UI](https://mui.com):** Biblioteca de componentes React baseados no Material Design da Google.
- **[Bootstrap](https://getbootstrap.com):** Framework CSS para estruturação de grid, responsividade e estilização rápida.
- **[React Router DOM](https://reactrouter.com):** Gerenciamento de rotas e navegação SPA (Single Page Application).
- **[Yarn](https://yarnpkg.com) / npm:** Gerenciamento de pacotes e dependências.

---

## 📂 Estrutura de Arquivos

```text
shopping/
├── public/               # Arquivos estáticos e index.html
├── src/                  # Código-fonte React (components, Pages, store/reducers/actions, routes.js)
├── package.json          # Dependências do projeto e scripts de execução
├── yarn.lock             # Árvore exata de versões das dependências instaladas via Yarn
└── README.md             # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto na Sua Máquina

### Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:
- **[Node.js](https://nodejs.org)** (versão LTS recomendada)
- **[Yarn](https://yarnpkg.com)** (recomendado, pois o projeto possui `yarn.lock`) ou **npm**
- **[Git](https://git-scm.com)**

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com
   ```

2. **Acesse o diretório do projeto:**
   ```bash
   cd shopping
   ```

3. **Instale as dependências:**
   Utilizando o Yarn:
   ```bash
   yarn install
   ```
   *(Ou, caso prefira utilizar o npm: `npm install`)*

4. **Inicie o servidor de desenvolvimento:**
   Utilizando o Yarn:
   ```bash
   yarn start
   ```
   *(Ou com npm: `npm start`)*

5. **Acesse a aplicação no navegador:**
   A aplicação abrirá automaticamente ou estará disponível em `http://localhost:3000/`.

---

## 📦 Gerando Build de Produção

Caso deseje gerar os arquivos otimizados para publicação em produção, execute:

```bash
yarn build
```
*(Ou `npm run build`)*

Os arquivos finais serão gerados na pasta `build/`.

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você quiser melhorar este projeto:

1. Faça um **Fork** do repositório.
2. Crie uma **Branch** para sua melhoria (`git checkout -b feature/NovaFuncionalidade`).
3. Faça o **Commit** das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`).
4. Faça o **Push** para a branch (`git push origin feature/NovaFuncionalidade`).
5. Abra um **Pull Request**.

---

## 👨‍💻 Autor

Desenvolvido por **[marceloxm](https://github.com/marceloxm)** durante os estudos na **Digital Innovation One (DIO)**.
