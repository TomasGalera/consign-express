# consigna-express

### Descripción y documentación de la función console.log()

La función console.log() sirve para imprimir mensajes en la consola del navegador o en la consola del backend. Es muy utilizada para comprobar que el código funcione, ya que nos permite ver el valor de variables, el resultado de operaciones y de las funciones.

### Parámetros de console.log()

- Parámetro obligatorio: console.log() no necesita parámetros obligatorios. Podés llamarlo sin argumentos, pero no generará ninguna salida. ej: console.log()
- Parámetros opcionales: Podés pasarle uno o más argumentos, que pueden ser de cualquier tipo: strings, números, objetos, etc. ej:: console.log("La operación fue correcta")

### Contenido que publicar en la consola

El contenido que se publica en la consola depende de si estamos trabajando en el front-end o en el back-end.

- Consola del Front-end:
  En la consola, podríamos poner información que nos ayude a entender cómo se está comportando la interfaz. Por ejemplo, podríamos verificar si una función que cambia el estilo de un botón está funcionando correctamente.
  
- Consola del Back-end:
  En un entorno backend, como Node.js, console.log() se usa para comprobar la lógica del servidor. Esto puede incluir la impresión de los datos que recibe el servidor, los resultados de consultas a la base de datos, o mensajes que indican si una operación fue exitosa o fallida.

Por ejemplo, en el home banking en el login en el front-end se podria pooner un console.log() diciendo si fue correcto o no el logeo y en el back-end hacer uno que muestre los datos que se solicitaron.

### Otros metodos de console

- console.error(): Para imprimir mensajes de error.
- console.warn(): Para imprimir advertencias.
- console.table(): Para mostrar datos tabulares (arrays u objetos) en formato tabla.
