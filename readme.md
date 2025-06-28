# Projeto Avaliação N3 - Redes

## Integrantes

- Leonardo Anders
- Lucas Setter Veiga
- Thiago Maes
- Geison Carlos Melo

## Descrição

Este projeto utiliza Docker Compose para criar um ambiente com quatro serviços: Nginx, WordPress, MySQL e phpMyAdmin.

O objetivo é configurar o Nginx como um proxy reverso para que a aplicação WordPress seja acessível apenas através do caminho `/prova`.

## Pré-requisitos

- Docker
- Docker Compose

## Como Executar

1.  Clone este repositório.
2.  Abra um terminal na pasta do projeto.
3.  Execute o seguinte comando para iniciar a aplicação:

    ```bash
    docker-compose up -d
    ```

## Acesso aos Serviços

Após a execução, os serviços estarão disponíveis nos seguintes endereços:

- **WordPress:** [http://localhost/prova](http://localhost/prova)
- **phpMyAdmin:** [http://localhost:8081](http://localhost:8081)
- **Página Padrão Nginx:** [http://localhost/](http://localhost/)