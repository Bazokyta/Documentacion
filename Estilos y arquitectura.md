**Clases:**
- Clase Alumno: Entidad que contiene la información.  
- Clase Curso: Gestor de la información.  
- Un Curso contiene una lista de objetos Alumnos permitiendo que, mediante el menú, el Curso sepa recorrer sus alumnos.

**Métodos:**
- En el setter del DNI se asegura de sean 8 números y 1 letra.  
- El método “establecer\_calificación” actúa como un filtro para asegurar que las calificaciones sean entre 0 y 10\.  
- El método “calcular\_media\_curso” procesa los datos de todos los alumnos sin tener que ir sumándolos uno a uno.

**Menú:**
- Uso de un bucle while True y un match menu para el tráfico de la aplicación.  
- El menú pide datos y los muestra, pero todas las operaciones se realizan dentro de las clases.

**Control de errores:**
- Se han implementado bloques try...except para garantizar que la aplicación no se detenga ante entradas inesperadas:
  * Gestión de medias: Uso de la excepción ZeroDivisionError en el cálculo de promedios en caso de no existir el módulo.
  * Validación del menú: Uso de la excepción ValueError en la entrada principal del sistema en caso de poner un  valor no numérico.
