# Atividade Docker com imagem ngix e mysql

Terceira atividade do curso Infrastructure and Cloud Computing 

Professor: João Victorino

## Alunos:

Leonardo Ananias do Nascimento Azogue 

Vinissius Vioti dos Santos 

## ***Descrição Atividade:*** 
Subir dois contêineres, nginx e mysql, mapeando a porta 80 do nginx para acesso pelo host e permitir que o contêiner do nginx tenha comunicação de rede no contêiner mysql. 
Enviar sequência de comandos na linha de comando ou o Docker-compose com os arquivos necessários para que a solução funcione.

*Utilizado a imagem Mysql, ngix e adminer"*

> Passo a passo
```
Baixar o código no github https://github.com/leonasci02/atividadeDocker.git
abra o Visual Code na pasta do projeto
Execute o comando:$ docker-compose up -d
Depois de tudo ok
Acesse seu navegador e abra duas abas a primeira aba adicione o link do ngix -> http:localhost:80
Na segunda aba adicione o link do Adminer um gerenciado web do mysql  -> http://localhost:8080
Adicione os seguinte registros:
Servidor : mysql-app
usuario: root
senha: Password1234!
Então será carregada a lista com as database padrão e a database root criada.

```
