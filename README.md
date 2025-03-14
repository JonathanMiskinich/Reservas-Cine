# Sistema de Reservas de Asientos para un Cine 

## Descripción 
Este proyecto es un sistema backend para gestionar las reservas de asientos en un cine. Permite a los usuarios reservar asientos, liberarlos y verificar la disponibilidad. El sistema está diseñado para ser eficiente, escalable y fácil de integrar con otras plataformas.

## Requisitos 
### Estructuras de datos
- **Matriz bidimensional**: Para representar la sala de cine (filas y columnas de asientos).
- **Hash set (HashSet)**: Para almacenar los asientos reservados y evitar duplicados.

### Algoritmos
- **Mejor asiento disponible**: Encuentra el mejor asiento disponible (por ejemplo, el más cercano al centro de la sala).
- **Asientos contiguos**: Sugiere asientos contiguos cuando un usuario reserve múltiples entradas.

### Patrones de diseño
- **Factory**: Para crear diferentes tipos de salas (2D, 3D, VIP).
- **State**: Para gestionar el estado de un asiento (disponible, reservado, ocupado).

### Lógica de programación
- **Validación de asientos**: Valida que un asiento no esté ya reservado antes de asignarlo.
- **Liberación de asientos**: Libera asientos si el usuario no completa la reserva en un tiempo límite.

## Tecnologías utilizadas 
- **Lenguaje de programación**: C#
- **Framework**: .NET Core
- **Estructuras de datos**: Matrices bidimensionales, hash sets.
- **Patrones de diseño**: Factory, State.
- **Herramientas**: Git, GitHub, Visual Studio.