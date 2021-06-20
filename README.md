# Local Docker MYSQL 5.7.29

Banco de dados para desenvolvimento provisionado pelo Docker.

## Serviços/acessos

- MYSQL 5.7 (utilizar mysql como host de conexão.)

## Pré-requisitos

* Docker instalado
* Docker compose instalado

## Instalação

* Clone o repositório
* Clone o arquivo `.env.example` para `.env` e modifique com as informações do seu local
* Execute o comando `docker-composer up -d` dentro da pasta clonada

## Comandos importantes
* Iniciar: `docker-composer up -d`
* Parar: `docker-compose down -v --remove-orphans`
* Reiniciar: `docker-compose down -v --remove-orphans && docker-compose up -d`


## Configuração/Variáveis ​​de ambiente
No arquivo `.env.example` é possível encontrar as configurações básicas dos serviços.