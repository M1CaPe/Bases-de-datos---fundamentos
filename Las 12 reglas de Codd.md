Las 12 reglas de Codd (https://www.mindmeister.com/app/map/1079684487?fullscreen=1&v=public)

Estas reglas se han convertido en un estándar de oro para evaluar la adhesión de un sistema de gestión de base de datos a los principios del modelo relacional. Sin embargo, no todas las bases de datos relacionales en uso hoy en día cumplen estrictamente con todas las 12 reglas.

1. Regla de la Información:

Toda la información en una base de datos relacional es representada de manera explícita en forma de valores en tablas.

2. Regla del Acceso Garantizado: 

Cada valor individual en la base de datos debe ser accesible mediante una combinación de nombre de tabla, valor de clave primaria y nombre de columna.

3. Regla del Tratamiento Sistemático de Datos Nulos:

  Se debe utilizar un mecanismo específico, independiente de los valores regulares, para representar información faltante y valores nulos.

4. Regla de la Vista Actualización: 

  Todas las vistas que son teóricamente actualizables deben ser actualizables por el sistema.

5. Regla de Sublenguaje Completo: 

  Un sistema de gestión de bases de datos debe soportar al menos un lenguaje que tenga una funcionalidad que sea completa tanto para definir la estructura de la base de datos como para manipular los datos almacenados en ella.

6. Regla de Actualización Dinámica en Línea: 

  Todas las operaciones en la base de datos deben ser capaces de realizarse en línea, sin necesidad de detener o bloquear la base de datos.

7. Regla de Independencia de Datos Físicos: 

  Los cambios en la estructura física de la base de datos no deben requerir cambios en las aplicaciones que interactúan con ella.

8. Regla de Independencia de Datos Lógicos: 

  Los cambios en la estructura lógica de la base de datos no deben requerir cambios en las aplicaciones que interactúan con ella.

9. Regla de Integridad de la Vista: 

  La integridad de las vistas debe ser garantizada por el sistema.

10. Regla de Distribución de Datos Independiente del Lenguaje: 

  El lenguaje utilizado para acceder a la base de datos no debe afectar la distribución de los datos.

11. Regla de la Independencia de la Distribución: 

  La distribución de la base de datos no debe ser visible para los usuarios de las aplicaciones.

12. Regla de la No Subversión: 

  Si un sistema de gestión de base de datos relacional tiene una interfaz de bajo nivel, esta interfaz no debe ser capaz de subvertir las reglas y restricciones expresadas en un nivel más alto.
