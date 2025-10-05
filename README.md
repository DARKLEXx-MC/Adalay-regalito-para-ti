# Proyecto San Valentín

Proyecto web interactivo para San Valentín con animaciones y efectos visuales.

## Estructura del Proyecto

```
Adalay/
├── index.html          # Página de inicio con nombre animado
├── carta.html          # Página con carta interactiva en sobre
├── flores.html         # Página con flores animadas
├── css/
│   ├── global.css      # Estilos globales y resets
│   ├── botones.css     # Estilos de botones compartidos
│   ├── inicio.css      # Estilos para la página de inicio
│   ├── carta.css       # Estilos para la carta
│   └── flores.css      # Estilos para las flores
├── js/
│   ├── carta.js        # Interacción de la carta
│   └── flores.js       # Script para flores
└── img/
    └── flowers.png     # Icono de flores
```

## Páginas

### 1. Inicio (index.html)
- Muestra el nombre "ADALAY" con efecto de brillo animado
- Botón para navegar a la carta
- Utiliza: `global.css`, `inicio.css`, `botones.css`

### 2. Carta (carta.html)
- Carta interactiva dentro de un sobre
- Clic en el sobre para abrir/cerrar
- Clic en la carta para leer
- Botones de navegación a flores o inicio
- Utiliza: `global.css`, `carta.css`, `botones.css`, `carta.js`

### 3. Flores (flores.html)
- Animación de flores creciendo
- Múltiples elementos de vegetación animados
- Botón para volver al inicio
- Utiliza: `global.css`, `flores.css`, `botones.css`, `flores.js`

## Características Técnicas

- **Responsive**: Adaptado para dispositivos móviles y escritorio
- **Animaciones CSS**: Transiciones y keyframes para efectos visuales
- **JavaScript Vanilla**: Sin dependencias externas
- **Semántica HTML5**: Estructura clara y accesible

## Navegación

```
Inicio → Carta → Flores → Inicio
```

## Personalización

### Colores
Los colores principales se definen en variables CSS en cada archivo:
- Carta: Variables en `:root` de `carta.css`
- Flores: Variables en `:root` de `flores.css`

### Animaciones
Las animaciones están en la sección de keyframes al final de cada archivo CSS.
Puedes ajustar las velocidades modificando los valores de `animation-delay` y `animation-duration`.

### Texto de la Carta
El contenido de la carta se encuentra en `carta.html` dentro del elemento con clase `.text`.

## Fuentes

- **Marck Script**: Para títulos decorativos
- **Montserrat**: Para texto general
- Cargadas desde Google Fonts

