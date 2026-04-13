# Actividad individual I : taller

## Orientaciones de desarrollo

Se dispondrá en plataforma un espacio para la entrega del taller número uno – **Diseño de Consultas avanzadas SQL** con base en el siguiente diagrama:

### Figura 1 - Diagrama Relacional Bases de Datos de Biblioteca
![alt text](image.png)

Fuente: Elaboración propia

## Consultas SQL a diseñar

### SUBCONSULTAS

1. Obtener los nombres y apellidos de los usuarios que han reservado un libro de la categoría "Fiction".

2. Mostrar el título y autor de los libros que están prestados.

---

### OPERADORES DE CONJUNTO

3. Encontrar los títulos de los libros que han sido reservados, pero no prestados.

4. Encontrar los títulos de los libros que han sido prestados, pero no reservados.

---

### EXPRESIONES CONDICIONALES

5. Mostrar un listado de todos los libros con un estado: "Disponible" si `AvailableCopies > 0`, o "Agotado" si no hay copias disponibles.

6. Mostrar los usuarios y clasifícalos como "Activo" si tienen libros prestados y "Sin actividad" si no.

---

### ANÁLISIS AGREGADO CON GROUP BY Y HAVING

7. Encontrar las categorías con más de 3 libros.

8. Mostrar los usuarios que tienen más de 2 libros reservados.

---

### INNER JOIN

9. Mostrar un listado de los nombres de usuarios y los títulos de los libros que han sido prestados.

10. Mostrar los nombres de usuarios y los títulos de los libros que han reservado.

---

### LEFT JOIN

11. Listar todos los libros junto con el nombre del usuario que los reservó, si es que existe una reserva.

12. Listar todos los usuarios junto con el título del libro prestado, si existe un préstamo.

---

### RIGHT JOIN

13. Listar todos los libros junto con los nombres de los usuarios que los han reservado, incluyendo los libros que no tienen reservas.

14. Lista todos los usuarios junto con los títulos de los libros prestados, incluyendo los usuarios que no han realizado préstamos.

---

### FUNCIONES ESPECIALIZADAS

15. Mostrar un listado de los títulos de los libros en mayúsculas.

16. Mostrar los nombres de los usuarios concatenados en un solo campo (Nombre Completo).

---

### FUNCIONES DE FECHA

17. Calcular el número de días que han pasado desde que se reservó cada libro.

18. Mostrar los préstamos que están pendientes de devolución (`ReturnDate` es NULL).

---

### FUNCIONES DE AGREGACIÓN

19. Calcular el total de copias disponibles para cada categoría.

20. Encontrar el número total de libros prestados por cada usuario.

---

## Nota importante

> Para facilitar el desarrollo de este taller se dispondrá en la plataforma virtual del archivo `db_library.sql` para que los estudiantes los descarguen y hagan las pruebas en sus respectivos servidores de prueba.

---

## Criterios de evaluación

- **Exactitud en la Sintaxis y Ejecución de las Consultas.**
- **Uso correcto de la sintaxis del lenguaje.**