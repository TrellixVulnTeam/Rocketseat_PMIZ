# Trilha ReactJS

## Chapter I

## Fundamentos do ReactJS

# **1 Configurando ambiente**

## 1.1 Introdução do módulo

## 1.2 Ambiente de Desenvolvimento

Faaaaaala dev! 💜

Nesse guia iremos configurar as ferramentas necessárias do ambiente de desenvolvimento para podermos colocar a mão na massa e aproveitar todo o conteúdo das aulas de ReactJS do Ignite.

## - Instalando o Node.js

Antes de mais nada, iremos instalar o Node.js. É nele onde vamos rodar o nosso código em ambiente de desenvolvimento (ou seja, durante o acompanhamento das aulas).

Você pode seguir o conteúdo do link abaixo para um passo a passo mais detalhado sobre como fazer (te espero aqui de volta).

[Instalando o Node.js](https://www.notion.so/Instalando-o-Node-js-d40fdabe8f0a491eb33b85da93d90a2f)

## - Instalando o Yarn

Agora que você está com o Node.js instalado na sua máquina, o próximo passo é instalar o gerenciador de pacotes Yarn.

O Yarn é a ferramenta utilizada nas aulas como gerenciador de pacotes padrão mas é um passo opcional, beleza? Se quiser, você pode usar o npm que foi instalado por padrão junto do Node.js no passo anterior.

Assim como para o Node.js, irei deixar aqui mais um mini guia com o passo a passo de como fazer:

[Instalando o Yarn](https://www.notion.so/Instalando-o-Yarn-eca6a13be5b3467d8d2f7be15c60f322)

## - Instalando e configurando o Visual Studio Code

Estamos quase finalizando tudo o que é necessário para começar desenvolver nossas aplicações com o React. 

Nessa última etapa iremos realizar a instalação do editor de texto usado nas aulas e também vou te passar algumas dicas de como melhorar ainda mais a sua experiência de uso nessa ferramenta:

[Instalando e configurando o VS Code](https://www.notion.so/Instalando-e-configurando-o-VS-Code-c26cc9f80edf4f3486b9756573038dbb)



## 1.3 Criando estrutura do projeto

Vamos criar uma pasta para o nosso primeiro projeto:

```tex
$ mkdir 01-github-explorer
```

Após criar a pasta, acessá-la.

Inicializar o repositório criandio o package.json

```tex
$ yarn init -y
```

Pode também ser criado pelo npm:

```tex
$ npm init -y
```

No package.json encontramos as informações principais do nosso projeto.

```json
{
  "name": "01-github-explorer",
  "version": "1.0.0",
  "main": "index.js",
  "license": "MIT"
}

```

Vamos instalrar bibliotecas:

```tex
$ yarn add react
```

Após a instalação do react o **package.json** será modificado e será criado a pasta **node_modules**.

```json
{
  "name": "01-github-explorer",
  "version": "1.0.0",
  "main": "index.js",
  "license": "MIT",
  "dependencies": {
    "react": "^17.0.2"
  }
}

```

Instalar o **react-dom**:

```tex
$ yarn add react-dom
```

**package.json**:

```json
{
  "name": "01-github-explorer",
  "version": "1.0.0",
  "main": "index.js",
  "license": "MIT",
  "dependencies": {
    "react": "^17.0.2",
    "react-dom": "^17.0.2"
  }
}

```

Após as instalações das bibliotecas, criar uma pasta de nome **src**. Nesta pasta ficará todo código JavaScript criado por nós.

Crie outra pasta chamada **public** onde ficarão os arquivos públicos da nossa aplicação.

Na pasta **public** criar um arquivo **index.html**. Dentro deste arquivo, iniciar o **html:5**:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

Altere apenas o título do **html**:

```html
<title>GitHub Explorer</title>
```







## 1.4 Configurando Babel

## 1.5 Configurando Webpack

## 1.6 Estrutura do ReactJS

## 1.7 Servindo HTML estático

## 1.8 Webpack Dev Server

## 1.9 Utilizando source maps

## 1.10 Ambiente dev e produção

## 1.11 Importando arquivos CSS

## 1.12 Utilizando SASS



