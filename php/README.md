# Rodando um Container PHP

Containers PHP podem ser executados com publicacao nativa em um servidor web apache, para isso basta que voce utilize as imagens com a nomenclatura -apache- disponiveis do [dockerhub oficial do php](https://hub.docker.com/_/php/);

## Usando um Dockerfile

O processo de build consiste na construção de uma imagem usando um arquivo Dockerfile;

Um arquivo [Dockerfile](https://docs.docker.com/engine/reference/builder/) funciona como um]tipo de receita no formato declarativo;

```sh
docker build . -t simple-php-app:v0.1
```

## Rodando a imagem criada anteriormente

No exemplo abaixo o build do conteudo deste diretorio foi usado como base para criacao de uma imagem com o php.info:

```sh
docker run -d -p 80:80 simple-php-app:v0.1
```

> Verifique se a execução foi bem sucedida utilizando o comando docker com "docker ps", utilizando a opção "-p" foi criado um bound para acesso ao container na porta 80 a partir da instência rodando a Docker Machine.
