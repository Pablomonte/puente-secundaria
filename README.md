# Puente a Secundaria

Herramientas para empezar la secundaria con confianza.

Material de apoyo para estudiantes de 5to y 6to grado de primaria en Cordoba,
Argentina, que tienen que rendir un examen libre para pasar a secundaria.

El sitio tiene dos partes por materia: **estrategia y procedimientos** (como leer
una consigna, mostrar el procedimiento, revisar antes de entregar) y **contenidos
del examen** (los temas concretos).

Los contenidos estan armados a partir de **tres examenes libres reales de 2025**
(Ciencias Naturales y Ciencias Sociales de 5to, Matematica de 6to, Lengua de 6to).
Son un ejemplo de lo que se puede tomar, **no un temario oficial**: cada escuela
define su propio formato, cuantas materias se rinden, si hay parte oral y cuanto
se necesita para aprobar. La pagina "Los examenes de 2025" explica que averiguar
en la escuela.

Sitio web: https://pablomonte.github.io/puente-secundaria/

## Desarrollo local

```bash
pip install mkdocs-material
mkdocs serve          # http://127.0.0.1:8000
mkdocs build --strict  # falla ante enlaces rotos o paginas fuera del nav
```

`NOTAS-FUENTE.md` (en la raiz, no se publica) registra la transcripcion de los
tres examenes, las anotaciones de la docente que corrigio las consignas, y la
fuente de cada dato factual. Antes de editar contenido de Ciencias Sociales o de
flora autoctona, leelo.
