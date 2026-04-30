# Proyectos de Diseño Web - Guía Completa

## 📋 Estructura del Proyecto

```
valentina_mejias/
├── noticias/                    # Proyecto 1: Portal de Noticias
│   ├── index.html              # Archivo HTML principal
│   └── assets/
│       ├── css/
│       │   └── styles.css       # Estilos del proyecto
│       └── img/                # Carpeta para imágenes
│
└── posicionamiento/            # Proyecto 2: Demostración de Posicionamientos
    ├── index.html              # Archivo HTML principal
    └── assets/
        ├── css/
        │   └── styles.css      # Estilos del proyecto
        └── img/                # Carpeta para imágenes
```

---

## 🎯 Requisitos Cumplidos

### ✅ Proyecto 1: NOTICIAS

**1. Punto: Publicación Correcta**
- Archivo HTML bien estructurado
- CSS optimizado y bien organizado
- Listo para publicar en hosting

**2. Puntos: Propuesta Gráfica**
- Tema: Portal de noticias moderno "NEXO"
- Jerarquía visual clara: Encabezado → Noticia destacada → Grid de noticias
- Recursos expresivos:
  - **Colores**: Gradientes azules profesionales, acentos rojo y naranja
  - **Tipografía**: Fuentes del sistema, pesos variados (300-900)
  - **Fondos**: Gradientes, degradados suaves
  - **Espaciado**: Proporciones armónicas

**3. Puntos: Uso Correcto de HTML y CSS**
- Etiquetas semánticas: `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Nombres de clases funcionales: `.main-header`, `.news-card`, `.featured-story`
- IDs significativos (si aplica)
- Variables CSS para mantenimiento
- Etiquetas bien cerradas

**4. Puntos: Posicionamientos (RELATIVE y ABSOLUTE)**
- **RELATIVE**: `.header-container`, `.featured-story`, `.card-image-container`
- **ABSOLUTE**: `.header-accent`, `.category-badge`, `.breaking-badge`, `.category-label`
- Todos identificados con comentarios en HTML

---

### ✅ Proyecto 2: POSICIONAMIENTO

**1. Punto: Publicación**
- Archivo HTML completo
- CSS modular y bien organizado

**2. Puntos: Propuesta Gráfica**
- Tema: Tutorial interactivo sobre posicionamientos
- Secciones claras y demostradas visualmente
- Diseño educativo con ejemplos prácticos
- Colores distintivos: Púrpura, verde menta, amarillo dorado

**3. Puntos: HTML y CSS Correctos**
- Etiquetas semánticas completas
- Clases descriptivas y funcionales
- Estructura lógica y clara
- Código bien indentado

**4. Puntos: Posicionamientos Demostrados**
- **RELATIVE**: `.relative-parent`, `.product-image-container`, `.price-container`
- **ABSOLUTE**: `.relative-child`, `.absolute-child`, `.discount-badge`, `.new-badge`, `.sale-label`
- Ejemplos visuales interactivos
- Comentarios explicativos en HTML

---

## 🚀 Cómo Usar en VS Code

### Abrir los Proyectos
1. Abre VS Code
2. Ve a `Archivo` → `Abrir carpeta`
3. Selecciona `c:\Users\Yvn\Desktop\jael\valentina_mejias`
4. Verás toda la estructura de carpetas

### Ver en el Navegador
1. **Opción 1**: Haz clic derecho en `index.html` → "Open with Live Server" (necesita extensión)
2. **Opción 2**: Arrastra el archivo `index.html` al navegador
3. **Opción 3**: Usa `python -m http.server` en la terminal

### Editar Archivos
- HTML: Modifica contenido, estructura, etiquetas
- CSS: Cambia colores, estilos, layouts en `assets/css/styles.css`
- Imágenes: Coloca archivos `.jpg`, `.png`, `.gif` en `assets/img/`

---

## 📸 Agregar Imágenes

### Para Proyecto NOTICIAS:
1. Coloca imágenes en: `noticias/assets/img/`
2. Nombres recomendados:
   - `featured.jpg` (imagen principal)
   - `news1.jpg`, `news2.jpg`, `news3.jpg`, `news4.jpg` (noticias)

### Para Proyecto POSICIONAMIENTO:
1. Coloca imágenes en: `posicionamiento/assets/img/`
2. Nombres recomendados:
   - `product-placeholder.jpg` (para el caso práctico)

---

## 🌐 Hosting Gratuito - Opciones

### Opción 1: GitHub Pages (RECOMENDADO - Más Fácil)
1. Crea una cuenta en GitHub.com
2. Crea un repositorio llamado `valentina_mejias`
3. Sube los archivos
4. Ve a Settings → Pages
5. Selecciona "Deploy from a branch" → rama "main"
6. ¡Listo! Tu sitio estará en: `https://tu-usuario.github.io/valentina_mejias/`

### Opción 2: Netlify
1. Ve a netlify.com
2. Registrate con tu cuenta GitHub
3. Conecta tu repositorio
4. Deploy automático
5. Tu sitio en: `https://algo-random.netlify.app/`

### Opción 3: Vercel
1. Ve a vercel.com
2. Conecta tu cuenta GitHub
3. Importa el repositorio
4. Vercel hace deploy automático

---

## 📝 Comentarios de Posicionamiento en HTML

Busca estos comentarios en el HTML para identificar elementos posicionados:

**NOTICIAS:**
```html
<!-- Elemento decorativo con posicionamiento ABSOLUTE -->
<span class="header-accent">●</span>

<!-- Etiqueta de categoría con posicionamiento ABSOLUTE -->
<span class="category-badge">Tecnología</span>
```

**POSICIONAMIENTO:**
```html
<!-- Contenedor con posicionamiento RELATIVE -->
<div class="parent-box relative-parent">

<!-- Elemento con posicionamiento RELATIVE -->
<div class="child-box relative-child">

<!-- Elemento ABSOLUTE posicionado dentro del RELATIVE -->
<div class="child-box absolute-child top-left">
```

---

## 🎨 Guía de Colores y Variables CSS

### Variables Definidas:
- `--primary-color`: Color principal del tema
- `--secondary-color`: Color secundario (acentos)
- `--accent-color`: Tercer color para detalles
- `--background-light/dark`: Fondos
- `--text-primary/light/white`: Textos

Para cambiar el tema completo, solo modifica estas variables en `:root {}`

---

## ✨ Mejoras Futuras

1. Agregar más animaciones
2. Implementar formularios
3. Añadir interactividad con JavaScript
4. Optimizar imágenes
5. Agregar SEO metatags
6. Hacer totalmente responsive

---

## 📞 Soporte

Para dudas sobre:
- **HTML**: Consulta w3schools.com/html
- **CSS**: Consulta w3schools.com/css
- **Posicionamiento**: Mdn.dev/css/position

---

**¡Tu proyecto está listo para publicar! 🚀**
