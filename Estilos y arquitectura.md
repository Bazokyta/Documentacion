**Clases:**

- Clase Alumno: Entidad que contiene la información.  
- Clase Curso: Gestor de la información.  
- Un Curso contiene una lista de objetos Alumnos permitiendo que, mediante el manú, el Curso sepa recorrer sus alumnos.

**Métodos:**

- En el setter del DNI se asegura de sean 8 números y 1 letra.  
- El método “establecer\_calificación” actúa como un filtro para asegurar que las calificaciones sean entre 0 y 10\.  
- El método “calcular\_media\_curso” procesa los datos de todos los alumnos sin tener que ir sumándolos uno a uno.

**Menú:**

- Uso de un bucle while True y un match menu para el tráfico de la aplicación.  
- El menú pide datos y los muestra, pero todas las operaciones se realizan dentro de las clases.