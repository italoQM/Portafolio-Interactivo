# Portafolio Interactivo

Landing page desarrollada para la **Práctica Calificada N° 3 (PC3)** del curso *Hojas de Estilo en Cascada Avanzado*.

## Tecnologías
- HTML5
- Bootstrap 5.3.3 (CDN)
- CSS3 puro (`styles.css`)

## Bootstrap 5
- **Navbar** responsive con menú hamburguesa (`navbar-expand-md`, `bg-dark`).
- **Grid**: `container`, `row`, `col-sm-12`, `col-md-4`, `col-md-6`.
- **Formulario** de contacto con `form-control`, `form-label` y `mb-3`.
- **Botones** `btn btn-primary` (Enviar) y `btn btn-secondary` (Limpiar) dentro de `d-grid gap-2`.

## Transformaciones 2D (con `transition`)
| Caja | Efecto en `:hover` |
|------|--------------------|
| Caja 1 | `rotate(8deg)` |
| Caja 2 | `scale(1.12)` |
| Caja 3 | `translateY(-20px) skewX(-8deg)` |

## Transformaciones 3D
Tarjeta que gira al pasar el mouse. El contenedor `.scene-3d` usa `perspective: 1000px`, la tarjeta `.flip-card` usa `transform-style: preserve-3d` y al hacer hover aplica `rotateX(15deg) rotateY(180deg)`. Las caras usan `backface-visibility: hidden`.

## Animaciones (`@keyframes`)
- `deslizarEntrada`: el título y subtítulo aparecen deslizándose desde la izquierda.
- `fondoMovil`: el degradado del hero se mueve constantemente.
- `latido`: el botón "Ver proyectos" late (escala y sombra).
- `orbeMagico`: círculo que cambia de color y tamaño infinitamente.
- `girar`: spinner de carga al inicio de la página y dentro del botón "Enviar".
- `ocultarLoader`: desvanece la pantalla de carga.

Se usan las propiedades `animation-duration`, `animation-iteration-count`, `animation-timing-function` y `animation-direction`.

## Responsividad
La página se adapta a móviles, tablets y escritorio sin desbordamiento horizontal.

## Autor
Italo Segundo Quispe Moreno (ItaloQM) — UTP
