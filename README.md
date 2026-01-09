# Quantum Library - Proyecto de Desarrollo Web

## 📋 Descripción del Proyecto

Este proyecto consiste en la recreación pixel-perfect de un diseño de librería online desarrollado en Figma, implementado con **HTML5 puro y CSS3** sin frameworks ni librerías externas.

## 🎯 Objetivo

Convertir un diseño de Figma en un sitio web funcional, manteniendo una fidelidad del 100% al diseño original en cuanto a:
- Colores exactos
- Tipografías
- Espaciado y layout
- Estructura de componentes
- Elementos visuales

## 🛠️ Proceso de Desarrollo

### 1️⃣ **Fase de Análisis del Diseño**
Usando antigravity para analizar el diseño
- Se proporcionó el enlace del proyecto en Figma: [System Design - Sergio - 2º DAW A](https://www.figma.com/design/zA7Qxx8bxebwjmqottIpLH/System-Design---Sergio---2%C2%BA-DAW-A?node-id=101-2107)
- Se adjuntaron **3 capturas de pantalla** del diseño para facilitar el análisis detallado:
  - Página Principal / Landing Page
  - Página Comprar Online (Tazas)
  - Página Comprar Online (Libros)

### 2️⃣ **Fase de Implementación Inicial**
Con base en las capturas proporcionadas, se extrajo:
- **Paleta de colores exacta**:
  - Header: `#B7DAFF`
  - Cards: `#BDEAE5`
  - Botones: `#1976D2`
  - Footer: `#00598F`
- **Tipografías**: Inter (contenido) y Roboto Mono (títulos)
- **Estructura**: Header con navegación, Hero section, grids de productos, sidebar de filtros, footer

Se generaron automáticamente:
- `index.html` - Página principal
- `shop.html` - Tienda de libros
- `shop-mugs.html` - Tienda de tazas
- `css/main.css` - Hoja de estilos completa

### 3️⃣ **Fase de Ajustes Manuales**
Se realizaron correcciones manuales para perfeccionar el diseño:

#### Ajustes realizados:
1. **Imágenes del Hero y Mapa**:
   - Se cambió `hero-quantum.jpg` → `hero.png`
   - Se cambió el placeholder del mapa → `mapa.png`

2. **Bordes y estilos**:
   - Se agregó `border-top: 2px solid #000` al header
   - Se agregó `border: 2px solid #000` a la sub-navegación
   - Se agregó `border: 2px solid #000` a los botones de navegación

3. **Tipografía de títulos de sección**:
   - Se cambió el color del texto a `black`
   - Se añadió `font-weight: bold`

4. **Color de las cards**:
   - Se corrigió el color a `#BDEAE5` (especificado exactamente)

5. **Adición de imágenes**:
   - Se agregaron manualmente las imágenes del proyecto en las carpetas correspondientes
   - Imágenes de libros en `../card/images/`
   - Imágenes del proyecto (hero, mapa, iconos) en `./images/`

## 📁 Estructura del Proyecto

```
libreria/
├── index.html           # Página principal
├── shop.html           # Tienda de libros
├── shop-mugs.html      # Tienda de tazas
├── css/
│   └── main.css        # Estilos globales
├── images/
│   ├── hero.png        # Imagen hero principal
│   ├── mapa.png        # Mapa de ubicaciones
│   ├── v101_2195.png   # Logo
│   ├── v101_2125.png   # Icono búsqueda
│   ├── v101_2148.png   # Icono usuario
│   └── v101_2698.png   # Icono configuración
└── README.md           # Este archivo
```

## 🎨 Características Técnicas

### HTML
- Semántico y accesible
- Sin uso de frameworks
- Estructura modular y reutilizable

### CSS
- Variables CSS para colores y estilos
- CSS Grid para layouts de productos
- Flexbox para componentes
- Diseño responsive
- Hover effects y transiciones

### Elementos Visuales
- **Cards de productos** con:
  - Imágenes de alta calidad
  - Badges (Nuevo/Oferta)
  - Precios destacados
  - Descripciones
  - Botones de compra
- **Sidebar de filtros** con checkboxes funcionales
- **Header fijo** con logo, búsqueda y navegación
- **Footer** con redes sociales y enlaces legales

## 🖼️ Páginas Implementadas

### 🏠 **Página Principal** (`index.html`)
- Hero section con imagen destacada
- Sección "Selección destacada" con 4 libros
- Localizador de tiendas con mapa interactivo
- Lista de ubicaciones físicas

### 📚 **Tienda de Libros** (`shop.html`)
- Sidebar con filtros de categorías
- Grid de 8 productos (libros)
- Vista de cards con toda la información

### ☕ **Tienda de Tazas** (`shop-mugs.html`)
- Mismo layout que la tienda de libros
- 4 productos de tazas temáticas
- Filtro "Tazas" activo

## 🚀 Cómo Visualizar el Proyecto

1. Abrir `index.html` directamente en cualquier navegador moderno
2. Navegar entre páginas usando los botones del header
3. No requiere servidor local (archivos estáticos)

## 📝 Notas del Desarrollo

- **Fidelidad al diseño**: Se priorizó la exactitud pixel-perfect sobre la simplificación
- **Compatibilidad**: Probado en navegadores modernos (Chrome, Firefox, Edge)
- **Responsive**: Se adaptó el diseño para tablets y móviles
- **Imágenes**: Las imágenes de libros provienen de la carpeta `card/images/`

## 👨‍💻 Autor

**Sergio Fernández Fernández**  
2º DAW A - Desarrollo de Interfaces Web

---

*Proyecto desarrollado con HTML5 y CSS3 puro, sin dependencias externas*
