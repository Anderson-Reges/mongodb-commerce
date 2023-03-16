# Projeto de estudo de querys e operadores de MongoDB desenvolvido na [Trybe](https://www.betrybe.com/)

# Sobre o Projeto
Este projeto trata-se de um estudo, dentro na pasta `challanges` a um serie de arquivos chamados desafios, cada um contem uma query escrita para consulta no banco MongoDB, utilizando os dados que estão na pasta `assets/produtos`.

## Técnologias usadas

<a href="https://www.mongodb.com/" >![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)</a>

## Instalando Dependências

```
npm install
``` 

## Executando aplicação

> Crie um container com um volume apontando para a pasta do projeto:
  - coloque o nome do container a vontade
```shell
docker run -d --name=nomeDoContainer -v "$PWD:/app" -p 27017:27017 mongo:5.0
```
> Com o container em execução, acesse o terminal do container:
```shell
docker exec -it nomeDoContainer bash
```
