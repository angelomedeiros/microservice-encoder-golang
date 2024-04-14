# Video Encoder Microservice

Este repositório contém um microserviço de encoder de vídeo, projetado para ser escalável e eficiente, utilizando uma arquitetura hexagonal para separação de preocupações e flexibilidade na integração de componentes. Desenvolvido em Go, este serviço utiliza RabbitMQ para mensageria, Bento4 para o processo de encoding de vídeo, Docker para containerização e PostgreSQL como banco de dados.

## Recursos

- **Linguagem de Programação**: Go
- **Mensageria**: RabbitMQ
- **Encoder de Vídeo**: Bento4
- **Containerização**: Docker
- **Banco de Dados**: PostgreSQL
- **Arquitetura**: Hexagonal, promovendo a separação entre o domínio, a aplicação e a infraestrutura.

## Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

- Docker
- Docker Compose
- Go (versão 1.15 ou superior)

## Configuração e Instalação

1. **Clonar o repositório:**

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```
