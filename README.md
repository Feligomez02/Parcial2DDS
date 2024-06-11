# Parcial2DDS
Realizamos un simulcaro de parcial de Desarrollo de Sw

Enunciado:
● Desarrollar el frontend de una aplicación utilizando 2 instancias de Visual Studio Code, una
para ejecutar el back en port 4000 y la otra para el front en port 3000. Se deberá generar una
funcionalidad nueva al proyecto de frontend existente.
● El proyecto del backend y frontend está en el siguiente repositorio GIT
https://github.com/arcba/EjercitacionBackEnd2024.git
● El proyecto del frontend está en el siguiente repositorio GIT
https://github.com/arcba/EjercitacionFrontEnd2024.git
Clonar ambos repositorios en la carpeta tmp de la estación de trabajo en linux. Y
realizar las modificaciones solicitadas en dichos proyectos.
Importante para instalar las librerías dependientes del back y del front:
1. Eliminar (si existe) el archivo package-lock.json en ambos proyectos.
2. Ejecutar el comando npm install en ambos proyectos (misma ruta donde está el
archivo package.json).
Consigna
Desarrollo del frontend: se deberá agregar una interfaz de consulta para el
recurso “empleados” , el cual ya posee desarrollado en el backend (verificar la ruta en
/api/empleados)
● Desarrollar un componente Empleado con el siguiente esquema:
● Agregar el código necesario para poder realizar la consulta de empleados. Se
deberá realizar los componentes de react y consumir el backend provisto.
● En el componente Empleado, incluir la interfaz de búsqueda con el campo a
filtrar (“ApellidoYNombre”) y el botón buscar.
Ciclo lectivo: 2024 Hoja:1/2
DESARROLLO DE SOFTWARE
Fecha: 10/06/2024
Deberá cumplir los siguientes requisitos:
● Consumir vía axios o fetch el endpoint del back.
● Utilizar para el formulario de búsqueda la librería react-hook-form
● En el componente EmpleadoListado incluir una tabla de html para mostrar
los resultados de la búsqueda, incluya en la misma todos los campos. (no se
pide paginación)
● En el componente Empleado se deberá agregar un botón para ingresar un
nuevo empleado, con lo cual se deberá invocar al componente
EmpleadoRegistro para permitir el ingreso del mismo. Realizar las
validaciones según definición de la base de datos.
● En el componente EmpleadoListado se deberá agregar a cada fila un botón
para editar el empleado, con lo cual se deberá invocar al componente
EmpleadoRegistro para permitir editar el mismo. Realizar las validaciones
según definición de la base de datos.
● En el componente EmpleadoListado se deberá agregar a cada fila un botón
para eliminar el empleado, con lo cual se deberá invocar al componente
EmpleadoRegistro para permitir eliminar el mismo.
● Agregar al componente menú de la aplicación, el acceso al nuevo
componente.
