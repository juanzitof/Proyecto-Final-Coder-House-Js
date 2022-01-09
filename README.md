## Proyecto Final de Curso de Java Script Coder House
## Simulador de Home Banking
Realizado durante la cursada del curso de JavaScript en Coder House.
## Librerias utilizadas en el proyecto
- [Jquery]v-3.6.0 
- [Bootstrap]v-5.1.3
- [Dayjs]v-1.8.21
- [Sweetalert2]v-11

## Para el funcionamiento del simulador
#### Inicio
- Al correr el simulador aparece la pantalla del login de ingreso en el que solicita un nombre de usuario y contraseña.
- Para poder ingresar, existen ya usuarios logeados (que se encuentran en el archivo users.json) los cuales son:

- Username mavelda12 | Password 1212
- Username josesp | Password 3619
- Username jacinlu | Password 6582

### Ya ingresado
- Los usuario ya tienen su numero de cuenta y la informacion pertinente de cada cuenta.
- La sesion de cada usuario es persistente, si se refresca la página la informacion no se elimina.
- Se muestra en una tabla las operaciones ya cargadas de cada usuario (que se encuentran en el archivo operations.json).
- Con la excepción del usuario jacinlu que no tiene operaciones y aparece cartel de vacio.

### Funcionalidad
- Se podra clickear 3 botones.
- **Depositar** : el usuario podra realizar un deposito a su propia cuenta actualizando el saldo y la tabla de ultimas operaciones.
- **Consular el valor del dolar** : el usuario podra visualizar el valor de venta y compra del dolar oficial y blue.
- **Logout** : el usuario puede abandonar la sesion, limpiando toda informacion almacenada, para poder ingresar 
  con el mismo o con otro usuario logeado.




Desarrollado por Juan Fuentes
