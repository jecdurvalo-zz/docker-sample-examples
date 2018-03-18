# Rodando um Container PHP

Containers PHP podem ser executados com publicacao nativa em um servidor web apache, para isso basta que voce utilize as imagens com a nomenclatura -apache- disponiveis do [dockerhub oficial do php](https://hub.docker.com/_/php/);

No exemplo abaixo o build do conteudo deste diretorio foi usado como base para criacao de uma imagem com o php.info:

```sh
docker run -d -p 8080:80 myphp-app
```
