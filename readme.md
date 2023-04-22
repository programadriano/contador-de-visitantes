# Contador de Visitantes

Este projeto é uma aplicação simples que utiliza Express, Redis, CORS e Docker para criar um contador de visitantes de um site.

## Pré-requisitos


Certifique-se de ter o Docker e o Docker Compose instalados em sua máquina.

[Docker](https://docs.docker.com/get-docker/)

[Docker Compose](https://docs.docker.com/compose/install/)

## Instalação

Clone o repositório:

```
git clone https://github.com/seu_usuario/contador-de-visitantes.git

cd contador-de-visitantes
```

Execute o comando *docker-compose up --build* no seu terminal para rodar o projeto.

## Rotas

* GET /visits: Retorna o número atual de visitantes.
* GET /api/curso: Incrementa o contador de visitantes e retorna uma mensagem de boas-vindas.

## Tecnologias Utilizadas

* Express: Framework web para Node.js
* Redis: Armazenamento de chave-valor em memória
* Docker: Plataforma para desenvolvimento, envio e execução de   aplicações em contêineres
* Docker Compose: Ferramenta para definir e executar aplicativos Docker de vários contêineres

## Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE.md para obter detalhes.


