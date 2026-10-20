# Formativa242

Actividad formativa 2.4.2 de CUY6142.
Programas en Python que consumen la API REST de SOM (Service Order Management).

Autor: Josefina_Vargas

## Programas

- `som_relocation.py`: crea una orden de relocalizacion y muestra los metros de cable,
  la duracion y los pasos del trabajo.
- `carga_masiva.py`: crea 50 ordenes de alta con datos al azar.
- `listar_ordenes.py`: lista todas las ordenes recorriendo las paginas de la API.

## Requisitos

- SOM v2 funcionando en `http://localhost:8081`.
- Python 3 con la libreria `requests`.
- Un token de SOM en la variable `key` de `som_relocation.py`.

## Como ejecutar

`python som_relocation.py`
