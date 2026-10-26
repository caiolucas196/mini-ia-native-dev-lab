# Painel de Demandas e Ações

## Objetivo
Sistema base da disciplina Projeto de Extensão em Software Full Stack.

## Funcionalidades
- Cadastrar demandas
- Listar demandas
- Excluir demandas
- Exibir resumo por status

## Tecnologias
- FastAPI
- SQLite
- HTML
- CSS
- JavaScript
- Docker
- Docker Compose
- Git

## Como executar
```bash
docker compose up --build
Endereços
Frontend: http://localhost:8080

API: http://localhost:8000/demands

Resumo: http://localhost:8000/summary

Docs da API: http://localhost:8000/docs


---

#### `backend/requirements.txt`
```text
fastapi
uvicorn[standard]
