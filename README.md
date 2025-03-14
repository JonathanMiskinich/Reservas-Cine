# Sistema de Reservas de Asientos para un Cine 

## Descripci�n 
Este proyecto es un sistema backend para gestionar las reservas de asientos en un cine. Permite a los usuarios reservar asientos, liberarlos y verificar la disponibilidad. El sistema est� dise�ado para ser eficiente, escalable y f�cil de integrar con otras plataformas.

## Requisitos 
### Estructuras de datos
- **Matriz bidimensional**: Para representar la sala de cine (filas y columnas de asientos).
- **Hash set (HashSet)**: Para almacenar los asientos reservados y evitar duplicados.

### Algoritmos
- **Mejor asiento disponible**: Encuentra el mejor asiento disponible (por ejemplo, el m�s cercano al centro de la sala).
- **Asientos contiguos**: Sugiere asientos contiguos cuando un usuario reserve m�ltiples entradas.

### Patrones de dise�o
- **Factory**: Para crear diferentes tipos de salas (2D, 3D, VIP).
- **State**: Para gestionar el estado de un asiento (disponible, reservado, ocupado).

### L�gica de programaci�n
- **Validaci�n de asientos**: Valida que un asiento no est� ya reservado antes de asignarlo.
- **Liberaci�n de asientos**: Libera asientos si el usuario no completa la reserva en un tiempo l�mite.

## Tecnolog�as utilizadas 
- **Lenguaje de programaci�n**: C#
- **Framework**: .NET Core
- **Estructuras de datos**: Matrices bidimensionales, hash sets.
- **Patrones de dise�o**: Factory, State.
- **Herramientas**: Git, GitHub, Visual Studio.