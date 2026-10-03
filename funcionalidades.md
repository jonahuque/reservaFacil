# Funcionalidades

## Funcionalidades para clientes

La aplicación estará orientada a que el proceso de reserva sea lo más sencillo posible.

### Registro e inicio de sesión

Los usuarios podrán crear una cuenta y acceder a la aplicación para gestionar sus reservas.

### Consulta de disponibilidad

El cliente podrá consultar las fechas y horarios disponibles antes de realizar una reserva.

### Realización de reservas

Para realizar una reserva, el usuario deberá seleccionar:

- Fecha.
- Hora.
- Número de personas.
- Datos necesarios para la reserva.

Una vez confirmada, la reserva quedará registrada en el sistema.

### Gestión de reservas

El usuario podrá consultar las reservas que haya realizado y, cuando sea necesario, modificar o cancelar una reserva.

## Funcionalidades para el establecimiento

El personal encargado podrá disponer de una zona de gestión para controlar la actividad del negocio.

Entre sus funciones estarán:

- Consultar las reservas del día.
- Crear nuevas reservas.
- Modificar reservas existentes.
- Cancelar reservas.
- Consultar información de los clientes.
- Gestionar la disponibilidad de mesas.
- Organizar horarios.

## Flujo básico de una reserva

```text
Cliente
   |
   v
Consulta disponibilidad
   |
   v
Selecciona fecha y hora
   |
   v
Indica número de personas
   |
   v
Confirma la reserva
   |
   v
Reserva registrada
   |
   v
Establecimiento recibe la información
```

## Experiencia de usuario

La aplicación buscará ofrecer una interfaz **clara, sencilla e intuitiva**, evitando pasos innecesarios.

El objetivo es que un cliente pueda completar una reserva en pocos pasos y que el establecimiento pueda consultar la información rápidamente.
