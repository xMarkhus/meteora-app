![Meteora](thumbnail.png)

# Meteora - E-commerce de Moda

O Meteora é um projeto de e-commerce em fase de desenvolvimento inicial. Este README fornece informações sobre o projeto, suas funcionalidades e como executá-lo em seu ambiente local.

![GIF da aplicação em execução](meteora-app.gif)

## 🔨 Funcionalidades do projeto

Neste estágio inicial de desenvolvimento, o Meteora possui as seguintes funcionalidades:

- Adicionar itens ao carrinho
- Remover itens do carrinho
- Visualizar a página do carrinho
- Deletar itens do carrinho

O [Figma dessa aplicação você encontra aqui](https://www.figma.com/file/R5ATrWK1nC44Eyeo6XZXlr/Meteora---Context-API?node-id=2386%3A2430&mode=dev).

## ✔️ Técnicas e tecnologias utilizadas

O projeto Meteora utiliza as seguintes tecnologias e bibliotecas:

- `React` - Framework JavaScript
- `Vite` - Build tool para desenvolvimento rápido
- `JavaScript` - Linguagem de programação principal
- `Context API` - Para gerenciamento de estado
- `useReducer` - Para controle de estado
- `useMemo` - Para otimização de desempenho
- `Bootstrap` - Framework de design e componentes

## 🛠️ Abrir e rodar o projeto

Para executar o projeto Meteora em seu ambiente local, siga estas etapas:

1. Certifique-se de ter o Node.js instalado em sua máquina.

2. Baixe o repositório do projeto:

3. Extraia os arquivos para uma pasta de sua preferência.

4. Navegue até a pasta em questão via terminal (cmd):

```bash
cd repo-meteora
```

5. Instale as dependências usando o npm:

```bash
npm install
```

6. Inicie o projeto localmente:

```bash
npm run dev
```

7. Abra seu navegador e acesse a url exibida no seu terminal para visualizar o projeto.

## 📚 Mais informações do projeto

O Meteora é um e-commerce fictício de moda em constante desenvolvimento. Este projeto visa aprimorar as habilidades em React, e apresentar a Context API como uma solução para gerenciamento de estados globais de uma aplicação React.

O design e protótipo deste projeto podem ser encontrados [aqui](https://www.figma.com/file/R5ATrWK1nC44Eyeo6XZXlr/Meteora---Context-API?node-id=2386%3A2430&mode=dev).

Aproveite o desenvolvimento e aprimoramento do Meteora!

# 🛍️ Meteora - Context API e Gerenciamento de Estados Globais

Bem-vindo ao **Meteora**! 🚀  
Este projeto foi desenvolvido para demonstrar como transformar uma aplicação com problemas de **Prop Drilling** em uma aplicação **escalável**, utilizando a **Context API** do React.  

Aqui você encontrará uma aplicação funcional de carrinho de compras, estruturada com boas práticas de desenvolvimento front-end.

---

## 🛠️ Funcionalidades Desenvolvidas

### 🔗 Gerenciamento de Estados Globais com Context API
- Criamos um contexto para gerenciar os estados globais da aplicação, cobrindo:
  - **Página Home**: Exibe os produtos disponíveis.
  - **Carrinho Suspenso**: Mostra os produtos adicionados ao carrinho, com opções de exclusão.

### 🪝 Hooks Customizados
- Encapsulamos lógicas complexas em hooks reutilizáveis, incluindo:
  - Adicionar produtos ao carrinho.
  - Remover produtos do carrinho.

### 🔄 Reducer
- Implementamos a função `carrinhoReducer()` para:
  - Gerenciar as operações do carrinho.
  - Atualizar os estados globais com base em ações específicas.

---
