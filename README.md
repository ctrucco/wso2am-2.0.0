![Docker Logo](https://github.com/ctrucco/wso2am-2.0.0/blob/master/vertigo-docker.png)
# wso2am-2.0.0
Wso2 API Manager

Roteiro:

* Dentro do diretório onde está o arquivo "yml" rodar o comando para subir o Compose.
  - docker-compose up

* Iniciar o Compose em background.
  - docker-compose up -d

* verificar containers funcionando e logs do compose
  - docker-compose ps

  - docker-compose logs -f

* Escalando os serviços do Api Manager com o Docker-Compose.
  - docker-compose scale wso2am=2
