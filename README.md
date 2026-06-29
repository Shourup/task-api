# task-api

CRUD-сервис для управления задачами. FastAPI + Docker + автодеплой.

### Локальный запуск

    conda create -y -n task-api python=3.11
    conda activate task-api
    pip install -r requirements.txt
    uvicorn app.main:app --reload

Документация: http://localhost:8000/docs

## Живой сервис

Документация и swagger: https://89-108-71-249.nip.io/docs