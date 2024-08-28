---
tutorial: "https://www.youtube.com/watch?v=jYK2i0_dtns"
---


# `16` Random Colors (Loop)

Hemos creado una función que devuelve un color basado en un número entre 0 y 3 (cualquier otro número retornará el color `black`).

Supongamos que somos profesores en un aula con 10 estudiantes y queremos asignar a **cada estudiante** un color aleatorio entre `red`, `yellow`, `blue` y `green`.

(solo 1 color por estudiante)

## 📝 Instrucciones:

1. Cambia la función `get_allStudentColors` para que devuelva una lista con 10 colores, en donde cada elemento de la lista representa el color asignado a cada estudiante.

## 💡 Pistas:

+ Tienes 10 estudiantes, necesitas que el ciclo itere 10 veces y añadir estos valores a una lista.

+ En cada iteración, genera un número aleatorio entre 0 y 3 usando la función `randint()` que hemos visto en ejercicios anteriores.

+ Usa la función `get_color` en este ejercicio, para saber qué color le corresponde al número obtenido.

+ Llama (ejecuta) la función `get_allStudentColors` e imprime su resultado en la consola.
