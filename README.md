<p align="center">
  <img src="https://res.cloudinary.com/dqqh1oigi/image/upload/v1594992537/Challenge%20Gostack%2006/GoStack_b27dh5.png" /> </br>
</p>

<h3 align="center">
  Desafio 02: Conceitos do Node.js
</h3>

<p align="center">
  <a href="#Introdução-memo"> Introdução </a>
   | 
  <a href="#Visualização-mag"> Visualização </a>
   | 
  <a href="#Execução-rocket"> Execução </a>
   | 
  <a href="#Tecnologias-computer"> Tecnologias </a>
</p>

## Introdução :memo:

Este projeto foi motivado pelo desafio 02 do [Bootcamp GoStack](https://rocketseat.com.br/gostack) e consiste em uma aplicação back-end para
armazenamento de repositórios de um portfólio. A aplicação é capaz de:

<p>
  <ol> 
    <li> Criar, listar, atualizar e remover repositórios; </li>
    <li> Permitir que cada repositório receba likes. </li>
  </ol>
</p>

## Visualização :mag:

Para criar um repositório, o cliente da aplicação deve enviar um arquivo JSON com os campos title, url e techs, conforme apresenta
a Figura 01:

<h6 align="center"> Figura 01 - Criar repositório </h6>
<p align="center">
  <img src="https://res.cloudinary.com/dqqh1oigi/image/upload/v1596297024/Challenge%20GoStack%2002/createRepository_ulfj87.png" /> 
  </br>
</p>

A listagem dos repositórios é apresentada na Figura 02. Note que além dos dados de cada repositório, são também apresentados seu
ID e número de likes:

<h6 align="center"> Figura 02 - Listar repositórios </h6>
<p align="center">
  <img src="https://res.cloudinary.com/dqqh1oigi/image/upload/v1596297024/Challenge%20GoStack%2002/listRepositories_t3cuuc.png" /> 
  </br>
</p>

Para atualizar um repositório, o cliente deve acessar a rota com o id do repositório e enviar através dela os dados atualizados, 
conforme é especificado na Figura 03:

<h6 align="center"> Figura 03 - Atualizar repositório </h6>
<p align="center">
  <img src="https://res.cloudinary.com/dqqh1oigi/image/upload/v1596297024/Challenge%20GoStack%2002/updateRepository_galgy1.png" /> 
  </br>
</p>

Similar a rota de atualizar repositório, o cliente deve acessar a rota de remoção com o id do repositório. Na Figura 04, o repositório 
Conceitos React JS é deletada:

<h6 align="center"> Figura 04 - Deletar repositório </h6>
<p align="center">
  <img src="https://res.cloudinary.com/dqqh1oigi/image/upload/v1596297024/Challenge%20GoStack%2002/deleteRepository_qtiyes.png" /> 
  </br>
</p>

Para curtir um repositório, o cliente também deve acessar a rota de likes com o id do repositório. Na Figura 05, o repositório 
Desafio 02 - Conceitos Node.js é curtido:

<h6 align="center"> Figura 05 - Curtir repositório </h6>
<p align="center">
  <img src="https://res.cloudinary.com/dqqh1oigi/image/upload/v1596297024/Challenge%20GoStack%2002/likeRepository_ffpzdw.png" /> 
  </br>
</p>

## Execução :rocket:

Para executar a API, siga as instruções:

<p>
  <ol>
    <li> Instalar dependências através do comando <b>yarn</b> </li>
    <li> Inicializar API no servidor através do comando <b>yarn dev</b> </li>
  </ol>
</p>

## Tecnologias :computer:

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Node JS](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)

