# Sistema de Gestión - Restaurante App (Semana 8)

## Información del Estudiante
* **Nombre Completo:** Anderson Johao Rodriguez Espinosa
* **Asignatura:** Programación Orientada a Objetos
* **Actividad:** Tarea Semana 8 - Aplicación de principios SOLID en un proyecto Python modular

---

## Descripción del Sistema
**restaurante_app** es una aplicación de consola modular desarrollada en Python diseñada para gestionar los productos, bebidas y clientes de un restaurante. El propósito principal de este proyecto es demostrar cómo un sistema de software puede mantenerse limpio, escalable y mantenible mediante una correcta distribución de responsabilidades y el uso de relaciones coherentes de herencia y polimorfismo.

El sistema permite:
1. Registrar productos genéricos y bebidas específicas validando la unicidad de sus códigos.
2. Registrar clientes verificando que no existan identificaciones duplicadas.
3. Listar todos los productos y bebidas almacenados haciendo uso de un comportamiento polimórfico común.
4. Listar los clientes registrados en el sistema.

---

## Estructura del Proyecto
El proyecto respeta estrictamente la arquitectura modular requerida, organizando las entidades de datos dentro del paquete `modelos`, los componentes lógicos dentro de `servicios` y el punto de entrada interactivo en la raíz:

```text
restaurante_app/
│
├── modelos/
│   ├── __init__.py
│   ├── producto.py
│   ├── bebida.py
│   └── cliente.py
│
├── servicios/
│   ├── __init__.py
│   └── restaurante.py
│
├── main.py
└── README.md
