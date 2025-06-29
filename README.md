# 🛍️ TechStore - Galería de Productos Optimizada

**TechStore**, una galería de productos e-commerce optimizada para ofrecer la mejor experiencia visual desde un móvil hasta un desktop 4K. 

---

## 🎯 Objetivo de la Misión

> Completar la implementación de imágenes responsive para una galería de productos, cuidando la experiencia del usuario y optimizando los recursos visuales según el dispositivo.

---

## 🧩 Funcionalidades Implementadas

### 🖼️ Imágenes Responsive
- Uso de `srcset` y `sizes` para servir imágenes en la resolución más adecuada.
- Carga adaptativa según el ancho del viewport.

### 🎨 Art Direction
- Uso del elemento `<picture>` para mostrar composiciones diferentes según el dispositivo (móvil vs desktop).
- Dirección artística aplicada en la primera tarjeta de producto.

### ⚡ Performance
- Implementación de `loading="lazy"` en imágenes.
- Uso de `aspect-ratio` para evitar **layout shifts** durante la carga.
- Imágenes en WebP cuando es posible.

### ♿ Accesibilidad
- Imágenes con `alt` descriptivo o `aria-label` si se usa `background-image`.
- Contraste correcto y estructura semántica para lectores de pantalla.

---

## 🧠 Detalles Técnicos

### 🎨 Variables CSS 
- Paleta personalizada (`--primary`, `--secondary`, `--accent`, `--cuaternary` , etc.).
- Tipografía y espaciado fluido con `clamp()`.

### 📐 Responsive Design
- Uso de **Grid Layout** adaptable con media queries:
  - `1 columna` en móvil
  - `2 columnas` en tablet
  - `3-4 columnas` en desktop y 4K
- Indicador de dispositivo (`📱 Mobile`, `💻 Tablet`, `🖥️ Desktop`) visible para depuración.

### 🧼 Estilo visual
- Tipografía moderna (`Poppins`).
- Tarjetas con `hover` suave y animaciones de entrada (`fadeInUp`).
- Botones interactivos con `:hover`, `transform` y `transition`.

---

## ✨ Resultado final

Una galería de productos elegante, optimizada, accesible y lista para usarse en cualquier tipo de dispositivo con un buen rendimiento y estética. 
