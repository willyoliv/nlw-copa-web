
<h1 align="center">NLW Copa - Web</h1>

![NLW Copa](https://user-images.githubusercontent.com/40326598/200138387-f97fb545-6de7-47aa-9d8f-a71f11ecb6a1.png)
---

<p align="justify">
  Frontend construído durante o evento NLW Copa disponibilizado pela Rocketseat que ocorreu entre os dias 31 de outubro de 2022 e 07 de novembro de 2022 . Durante o evento foram construídas três aplicações na Trilha Ignite, sendo elas: a interface Web para cadastro de bolões, a aplicação mobile para criar, visualizar e compartilhar bolões e por fim a aplicação backend usada para fornecer os dados e serviços para o funcionamento das outras duas.
</p>

<p align="center">
 <a href="#sobre-o-projeto">Sobre o projeto</a> |
 <a href="#layout">Layout</a> | 
 <a href="#como-usar">Como usar</a>
</p>

<h4 align="center">
	 Status: Finalizado
</h4>
 
### Sobre o projeto💻

 Este é o repositório da aplicação web. Esta é a versão resumida do projeto de bolões criado durante o evento NLW Copa, sendo utilizado o framework NextJs para a criação 
 da página web usando o recurso de SSR presente nativamente no Next.

#### Feature

- [X] Cadastro de bolões

#### Tecnologias🚀

As seguintes ferramentas foram usadas na construção do projeto:

- [x] [TypeScript](https://www.typescriptlang.org/).
- [X] [Node](https://nodejs.org/pt-br/).
- [x] [Nextjs](https://nextjs.org/) - Usado para a construção das telas.

##### Auxíliares

- [x] [Reactjs](https://reactjs.org/)

##### Padronização de código:

- [x] [ESLint](https://eslint.org/);
- [x] [Prettier](https://prettier.io/).
___
### Layout
Você pode visualizar o layout do projeto através [Deste link](https://www.figma.com/file/VnnLfmov3ZBOOG78Llhy06/Bol%C3%A3o-da-Copa-(Community)). É necessário ter conta no Figma para acessá-lo.

![nlw-copa-web](https://user-images.githubusercontent.com/40326598/200142849-7df8e26a-d444-433b-aec6-de66239dbae3.png)

___
### Como usar
#### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

**Obs:** Este projeto depende diretamente do projeto [nlw copa server](https://github.com/willyoliv/nlw-copa-server), sendo necessário executar o server primeiro e configurar o arquivo `.env` com a url em que o projeto server está funcionando.

##### Clone este repositório
```bash
git clone https://github.com/willyoliv/nlw-copa-web.git
```
##### Após clonar, acesse as pastas do projeto no terminal/cmd e instale as dependências
```bash
cd nlw-copa-web
npm install
# ou npm i
```

##### Para executar o projeto rode o seguinte comando
```bash
npm run dev
```

**Obs:** O projeto irá por padrão rodar em `http://localhost:3000`

---

