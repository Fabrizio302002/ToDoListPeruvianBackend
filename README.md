# Proyecto ToDoListPeruvian API


## Insignias


## Índice

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Requisitos](#requisitos)
- [Estado del Proyecto](#estado-del-proyecto)
- [Demostración de Funciones y Aplicaciones](#demostración-de-funciones-y-aplicaciones)
- [Acceso al Proyecto](#acceso-al-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Personas Contribuyentes](#personas-contribuyentes)
- [Personas Desarrolladoras del Proyecto](#personas-desarrolladoras-del-proyecto)
- [Licencia](#licencia)

## Descripción del Proyecto

Este proyecto es una API REST para la gestión de tareas, que permite crear nuevos usuarios, realizar validaciones y manejar errores de manera efectiva. Proporciona un conjunto de endpoints para interactuar con los datos de los usuarios.


## Estado del Proyecto

- **En Desarrollo**: El proyecto está en fase de desarrollo activo y se están implementando nuevas funcionalidades.
- **Version**: 1.0.0

## Requisitos

- **JDK**: Java 11 o superior
- **Maven**: Para la gestión de dependencias
- **h2**: Base de datos (o cualquier otra base de datos que estés usando)
- **Postman**: Herramienta opcional para probar la API

## Estado del Proyecto

- **En Desarrollo**: El proyecto está en fase de desarrollo activo y se están implementando nuevas funcionalidades.
- **Versión**: 1.0.0

## Demostración de Funciones y Aplicaciones

### Ejemplo de Uso

- **Crear un usuario**: `POST /api/register`

**Cuerpo de la solicitud**:

```json
{
	"email" :"yara@hotmail.com",
	"name" : "yara",
	"password" : "12345678"
}
```

**Respuesta Exitosa**:


```json
Código de estado: 201 Created
Cuerpo de la respuesta:

{
   "code": 0,
   "message": "Usuario Creado Existosamente"
}
```
	
 ### Errores Comunes
- **400 Bad Request**: Si hay errores de validación.
- **409 Conflict**: Si el correo ya está registrado.
- **500 Internal Server Error**: Para errores no manejados.

### Acceso al Proyecto

```bash
git clone https://github.com/Fabrizio302002/ToDoListPeruvianBackend.git
```

```bash
cd createuser
```

## Tecnologias utilizadas
- **Java**: JDK 11 o superior
- **Spring Boot**: Para la creación de la API REST
- **Maven**: Para la gestión de dependencias
- **H2Dialect**: Base de datos utilizada
- **Postman**: Herramienta para probar la API

## Personas Contribuyentes
Fabrizio302002 - Desarrollador Principal


## Personas Desarrolladoras del Proyecto
Fabrizio302002: Desarrollador Principal

## Licencia
Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo LICENSE.

### Instrucciones:
`README.md`
