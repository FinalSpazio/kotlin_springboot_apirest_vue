# Aplicação em Kotlin Spring Boot REST


## Pré-requisitos

Desenvolvido em: 
Linguagem de programação: Kotlin 1.4
Compilador: Java 11 - JDK
FrontEnd: Vue Js
Banco de dados: Oracle
Bibliotecas: em `requirements.txt`
IDE: Visual Studio
Sistema Operacional: Windows 10 Pro/Linux

### Guia de instalação

1º Passo: Criar um ambiente virtual: `virtualenv my_env --no-download`

2º Passo: Ativar ambiente virtual: `myenv/Scripts/activate`

3º Passo: instalar as libs contidas no arquivo requirements.txt: `[...] requirements.txt`

...


#### Docker (???)

Criar container:

*python:3.7-slim*
`docker build --no-cache --build-arg ENV=dev  --build-arg PORT=8000  --build-arg HOST=0.0.0.0   --build-arg ALLOWED_HOSTS = ['127.0.0.1','api-myproject.com.br']  --build-arg DATABASE_ENGINE=Oracle_kotlin  --build-arg DATABASE_NAME=Oracle_db_Name  --build-arg DATABASE_HOST=Oracle_host  --build-arg DATABASE_USER=Oracle_user  --build-arg DATABASE_PASSWORD=Oracle_password  --build-arg DATABASE_PORT=1521  --build-arg SERVICE_NAME=ORCL  --build-arg REDIS_CACHE_HOST=127.0.0.1  --build-arg REDIS_CACHE_PORT=6379  --build-arg REDIS_CACHE_DB=0  --build-arg REDIS_CACHE_PASSWORD=Your2020Redis  --build-arg IMG=zenika/kotlin  --build-arg STAGE='dev' -t myproject -f Dockerfile .`


Excecutar container:

`docker run -v <Source-path>:<container-path> -p <EXTERNAL-port>:<EXPOSE-port> <nome_do_container>`
`ex: docker run -v /c/DATABASE/:/app/base -p 8000:8000 myproject  `



### Autoria e contribuições

· Desenvolvedores: 
    - Franclin Souza
    - Jackson Santos
    - Jefferson Pinheiro
    - Leonardo Rodrigues
    - Ricardo Castro
    - Victor Freitas