[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23564893&assignment_repo_type=AssignmentRepo)
# Patrones Estructurales: Adapter y Facade

Este repositorio acompaña una clase de **Análisis y Diseño Orientado a Objetos** sobre patrones estructurales.

## Teoría

Los patrones estructurales describen formas de organizar clases y objetos para construir soluciones más grandes sin aumentar innecesariamente el acoplamiento.

Su objetivo principal es:

- simplificar la colaboración entre objetos,
- mejorar la reutilización de componentes,
- facilitar el mantenimiento,
- hacer más flexible la evolución del sistema.

### Adapter

El patrón `Adapter` permite que dos clases con interfaces incompatibles trabajen juntas.

- Se usa cuando ya existe una clase útil, pero su interfaz no coincide con lo que espera el cliente.
- Su propósito principal es la **compatibilidad**.
- Actúa como un traductor entre el cliente y el objeto existente.

### Facade

El patrón `Facade` ofrece una interfaz más simple para interactuar con un conjunto de clases o subsistemas.

- Se usa cuando el cliente tendría que coordinar demasiados objetos o pasos.
- Su propósito principal es la **simplicidad**.
- Actúa como un punto de entrada de alto nivel que organiza el trabajo interno.

### Diferencia clave

- `Adapter` traduce una interfaz.
- `Facade` simplifica el acceso a un sistema complejo.

## Estructura del repositorio

```text
patrones-estructurales-adapter-facade/
|-- ejemplos/
|   |-- README.md
|   |-- adapter_ejemplo.py
|   `-- facade_ejemplo.py
|-- ejercicio/
|   |-- README.md
|   `-- tienda_online_base.py
`-- .gitignore
```
