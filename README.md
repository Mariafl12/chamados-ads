# API de Chamados de Suporte

**Estudante:** Maria da Conceição Freitas Lopes
**Matricula:** 2023011420

## Objetivo
Estrutura inicial de uma API de chamados de suporte com Flask, gerenciada com uv. Nesta etapa existe apenas a rota inicial, sem cadastro de chamados nem banco de dados.

## Instalação
```bash
uv sync --locked
```

## Execução
```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Rota inicial
`GET /` em `http://localhost:5000/` retorna status `200`, `Content-Type: application/json` e o corpo:

```json
{"mensagem": "API de chamados em funcionamento"}
```