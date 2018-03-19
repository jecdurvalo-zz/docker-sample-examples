# Docker Sample Examples

Exemplos simples de aplicaçes usando node, php, java e SGBD executados em containers;

![alt tag](https://github.com/fiapsecdevops/docker-sample-examples/raw/master/img/machine.png]

## Criando uma instância para testes usando Docker

Esse template foi criado para lançamento de uma instância na AWS utilizando Cloud Formation, esta instância "nasce" com o Docker Community instalado na versão 17 e com acesso configurado para um usuário local;

Clique no link abaixo caso deseja utilizar este template:

[![cf-template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=sandboxDocker&templateURL=https://s3.us-east-2.amazonaws.com/cf-templates-fiaplabs/dockermachine-aws-tmpl.json)

***Importante:***

Para utilizar o template é necessário acesso a uma conta válida na AWS, se for necessário o uso fora dos laboratórios de aula será necessário o cadastro de uma [Free Tier](https://aws.amazon.com/pt/free/) ou de algum outro modelo de conta disponivel.
