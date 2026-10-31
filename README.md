# Autenticación con CSS Baseline 2026

Este repositorio contiene un componente BASE de entrada de datos (Input) para formularios de autenticación desarrollado con las últimas especificaciones de **CSS moderno (Baseline 2026)**. El objetivo principal es demostrar interacciones dinámicas y accesibles sin depender de JavaScript.

---

## Características principales

*   **Arquitectura CSS Limpia:** Organización avanzada mediante capas de cascada (`@layer`) divididas en `motor`, `base` y `componentes`.
*   **Encapsulación Nativa:** Uso de `@scope` para aislar los estilos del componente `.control-formulario` de forma segura.
*   **Modo Claro/Oscuro Nativo:** Implementación de la función `light-dark()` con el espacio de color `oklch()` para un soporte adaptativo del esquema de color del sistema.
*   **Validación de Formulario Nativa:** Control de estados visuales dinámicos (`:focus`, `:user-invalid` y `:user-valid`) usando selectores avanzados como `:has()`.
*   **Accesibilidad (A11y):** Inclusión de una clase `.sr-only` para lectores de pantalla, manteniendo una experiencia totalmente accesible.
*   **Tipografía Fluida y Escalable:** Uso de la función `clamp()` para calcular tamaños de fuente dinámicos y adaptables a cualquier resolución de pantalla (responsive sin *media queries*).


---

## Tecnologías utilizadas

*   HTML5
*   CSS Moderno (Baseline 2026)
    *   Cascading Layers (`@layer`)
    *   Scoped CSS (`@scope`)
    *   Función `light-dark()`
    *   Espacio de color `oklch()`
    *   Selector relacional `:has()`
    *   Pseudoclases `:user-invalid` y `:user-valid`
    *   Función de tipografía dinámica (`clamp()`)
      
