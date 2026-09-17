# Biblioteca - Aulas 04 e 05

Projeto Django consolidado das Aulas 04 e 05.

## Funcionalidades
- Cadastro de livros
- Tipo de acervo: Digital ou Físico
- Categorias 000 a 900
- Pesquisa por nome/título
- Filtro por tipo
- Filtro por categoria
- Django Admin

## Executar

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

Acesse:
- http://127.0.0.1:8000/livros/
- http://127.0.0.1:8000/admin/
