# Portafolio Interactivo - PC3

Proyecto desarrollado con Bootstrap 5, transformaciones y animaciones CSS.

## 1. Estructura y Framework (Bootstrap 5)
- Barra de navegación (Navbar) responsive con menú colapsable (hamburguesa).
- Sistema de Grid con `container`, `row` y columnas `col-sm-12 col-md-4`.
- Formulario de contacto con campos Nombre, Email, Mensaje y botones con `d-grid gap-2`.

## 2. Transformaciones y Transiciones 2D
Se aplicaron efectos `:hover` con `transition: transform 0.4s ease`:
- **Caja 1:** Rotación mediante `transform: rotate(15deg)`.
- **Caja 2:** Escalado mediante `transform: scale(1.1)`.
- **Caja 3:** Traslación hacia arriba mediante `transform: translateY(-15px)`.

## 3. Transformación 3D
- Contenedor padre con `perspective: 800px`.
- Elemento hijo con `transform-style: preserve-3d` y transición de 0.5s.
- Efecto `:hover` con rotación en dos ejes: `transform: rotateX(20deg) rotateY(-20deg)`.

## 4. Animaciones CSS (@keyframes)
- **Animación personalizada:** `@keyframes deslizar` para el título principal con duración de 1.5s y efecto `ease-out`.
- **Loader:** Círculo animado girando de 0 a 360 grados de forma infinita con `@keyframes girar` y `animation-timing-function: linear`.
