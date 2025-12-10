Prework – Automation Developer II (30 min antes de la entrevista)

Este prework tiene como objetivo ver tu forma de estructurar una solución en Python.


✅ Instrucciones

Crea un repositorio en tu propio GitHub con el nombre:
automation-developer-prework-[TU-NOMBRE]
(Ejemplo: automation-developer-prework-Paula-Granda)

Copia la siguiente estructura mínima:

root/
  ├── python/
  │     └── ejercicio_prework_csv_json.py
  ├── input/
  │     └── sample.csv   (usa el que te compartimos o crea uno de ejemplo)
  └── output/
        (aquí se generará data.json)


Implementa en python/ejercicio_prework_csv_json.py una solución en Python que:

Lea el archivo input/sample.csv

Procese las columnas: name, email, city

Genere un archivo output/data.json con una lista de objetos como:

[
  {
    "name": "John Doe",
    "email": "john@example.com",
    "city": "Medellín"
  },
  ...
]


Incluya manejo básico de errores, por ejemplo:

Cuando el archivo no exista

Cuando falte alguna de las columnas esperadas (name, email, city)

Tiempo estimado: 20–30 minutos.


Al finalizar:

Asegúrate de que tu script se pueda ejecutar sin errores.

Sube los cambios a tu repositorio en GitHub.

Envíanos el link de tu repositorio antes de la entrevista.

