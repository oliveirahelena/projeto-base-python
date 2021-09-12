# Projeto Base Python

Projeto base para iniciar qualquer projeto Python.

## Instalar dependências

```bash
pipenv install --dev -e .
```

## Instalar os scripts configurados do pre-commit

```bash
pipenv run pre-commit install -t pre-commit
pipenv run pre-commit install -t pre-push
```

## Rodar o Bandit

```bash
pipenv run python -m bandit .
```

## Rodar o Safety

```bash
pipenv run python -m safety check
```