# Tecnologías

## Arquitectura del proyecto

ReservaFácil estará compuesto por diferentes partes que trabajarán conjuntamente.

De forma general, el sistema contará con:

- **Aplicación móvil** para los clientes.
- **Aplicación de escritorio o interfaz de gestión** para el establecimiento.
- **Backend** encargado de procesar las peticiones.
- **API** para la comunicación entre aplicaciones.
- **Base de datos** para almacenar la información.
- Posible **integración con un ERP** para ampliar la gestión del negocio.

## Comunicación entre aplicaciones

La aplicación móvil y la aplicación de gestión se comunicarán con el backend mediante una API.

El flujo general será similar al siguiente:

```text
Aplicación móvil
       |
       | Petición
       v
     API REST
       |
       v
    Backend
       |
       v
Base de datos
```

De esta forma, las diferentes aplicaciones podrán utilizar una información centralizada.

## Ejemplo de petición

Un ejemplo simplificado de una petición podría ser:

```java
GET /api/reservas

// Devuelve las reservas disponibles
```

El backend procesará la petición y devolverá la información correspondiente.

## Tecnologías

Durante el desarrollo se podrán utilizar diferentes tecnologías y herramientas relacionadas con el ciclo de desarrollo de aplicaciones:

- Java.
- Android.
- Bases de datos SQL.
- APIs REST.
- Git y GitHub.
- Herramientas de desarrollo como IntelliJ IDEA y Android Studio.

La elección definitiva de cada tecnología podrá modificarse durante el desarrollo del proyecto en función de las necesidades que aparezcan.

## Futuras ampliaciones

El sistema podría incorporar posteriormente nuevas funcionalidades, como estadísticas, notificaciones, integración con sistemas externos o nuevas herramientas de gestión.

> **Importante:** la arquitectura definitiva se concretará durante las siguientes fases del proyecto.
