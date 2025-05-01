# Hola Mundo Flask CI/CD

Este repositorio contiene una aplicación básica en Flask para demostrar integración y entrega continua (CI/CD) con GitHub Actions.

## Pasos del workflow

- Instala las dependencias desde `requirements.txt`
- Ejecuta pruebas unitarias con `pytest`
- Genera una imagen Docker

## Cómo ejecutar localmente

```bash
pip install -r requirements.txt
python app.py
```

Abre en tu navegador: [http://localhost:5000](http://localhost:5000)

## Ejecutar pruebas

```bash
pytest
```
