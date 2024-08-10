# Docker Todo-List

Este é um projeto para containerização de uma aplicação fullstack utilizando Docker. O objetivo do projeto foi containerizar as aplicações, estabelecer conexões entre elas e orquestrar o funcionamento de todos os componentes.

## Visão Geral

O Docker Todo-List é composto por múltiplos contêineres que trabalham juntos para fornecer uma aplicação funcional. Cada parte da aplicação, como o front-end, back-end e banco de dados, foi containerizada individualmente. A comunicação entre esses contêineres é gerenciada para garantir o funcionamento coeso da aplicação.

## Funcionalidades

- **Containerização de Aplicações**: Cada componente da aplicação foi containerizado utilizando Docker.
- **Conexão entre Contêineres**: Configuração de redes Docker para permitir a comunicação entre os contêineres.
- **Orquestração de Contêineres**: Uso de Docker Compose para gerenciar e orquestrar os contêineres, garantindo que a aplicação funcione corretamente.

## Tecnologias Utilizadas

- **Docker**: Para criar e gerenciar os contêineres.
- **Docker Compose**: Para orquestrar a execução dos contêineres e gerenciar as dependências entre eles.
- **Front-end**: Tecnologia usada para o front-end da aplicação (por exemplo, React, Angular, etc.).
- **Back-end**: Tecnologia usada para o back-end da aplicação (por exemplo, Node.js, Express, etc.).
- **Banco de Dados**: Tecnologia usada para o banco de dados (por exemplo, MySQL, PostgreSQL, etc.).

## Estrutura do Projeto

- **docker-compose.yml**: Arquivo de configuração do Docker Compose, que define os serviços, redes e volumes usados pela aplicação.
- **Dockerfile**: Arquivos Dockerfile para construir as imagens de cada parte da aplicação.
- **src/**: Diretório contendo o código-fonte da aplicação.

## Como Executar o Projeto

1. **Clone este repositório**:

   ```bash
   git clone git@github.com:chatacks/docker-todo-list.git
   cd docker-todo-list
   ```

2. **Inicie os contêineres**:

   ```bash
   docker-compose up --build
   ```

3. **Acesse a aplicação**:

   A aplicação estará disponível em `http://localhost:3000` (ou outra porta configurada no `docker-compose.yml`).

## Parar a Aplicação

Para parar e remover os contêineres criados, utilize:

```bash
docker-compose down
```

## Contribuição

Contribuições são bem-vindas! Você pode abrir issues para relatar problemas ou sugerir melhorias. Pull requests também são apreciados.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Referências

- [Documentação do Docker](https://docs.docker.com/)
- [Documentação do Docker Compose](https://docs.docker.com/compose/)
