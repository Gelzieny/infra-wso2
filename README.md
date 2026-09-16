# WSO2 API Manager - Ambiente Local

Ambiente local do WSO2 API Manager utilizado para desenvolvimento
e testes de integração com o Portal Estadual de Inteligência
Artificial - GO.IA.

## Objetivo

Disponibilizar uma instância local do WSO2 API Manager para permitir:

- cadastro de APIs de teste;
- consulta das APIs cadastradas;
- testes da Publisher REST API;
- testes de autenticação OAuth2;
- desenvolvimento da integração WSO2 → Portal GO.IA;
- desenvolvimento da sincronização de APIs.

## Pré-requisitos

- Docker
- Docker Compose

Verifique:

```bash
docker --version
docker compose version

```

## URLs:

```text
- Portainer
  https://localhost:9443

- WSO2
  https://localhost:9444

- WSO2 Publisher
  https://localhost:9444/publisher

- WSO2 Developer Portal
  https://localhost:9444/devportal
```
