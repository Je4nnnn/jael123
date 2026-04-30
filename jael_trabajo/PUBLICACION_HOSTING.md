# 🌐 GUÍA COMPLETA: Publicar tu Proyecto en Hosting Gratuito

## 📌 Opciones de Hosting Gratuito

Tienes **3 opciones principales**, todas completamente gratuitas:

---

## OPCIÓN 1: GITHUB PAGES ⭐ (RECOMENDADO)

### ¿Por qué elegir GitHub Pages?
- ✅ Totalmente gratuito y ilimitado
- ✅ Ideal para sitios estáticos (HTML/CSS)
- ✅ Vinculado directamente a tu código
- ✅ Dominio: `https://tu-usuario.github.io/`
- ✅ Actualizaciones automáticas

### Pasos de Publicación:

#### Paso 1: Crear Cuenta en GitHub
1. Ve a https://github.com
2. Haz clic en "Sign up"
3. Completa el formulario:
   - **Username**: (tu nombre de usuario - importante, será parte de tu URL)
   - **Email**: tu correo
   - **Password**: contraseña segura
4. Verifica tu correo
5. ¡Cuenta creada! 🎉

#### Paso 2: Crear un Nuevo Repositorio
1. Haz clic en tu avatar (arriba a la derecha)
2. Selecciona "Your repositories"
3. Haz clic en botón verde "New"
4. Rellena:
   - **Repository name**: `valentina_mejias` (IMPORTANTE: usa exactamente este nombre)
   - **Description**: "Portal de noticias y tutorial de posicionamiento CSS"
   - **Public**: ✅ SELECCIONA ESTO
5. Haz clic en "Create repository"

#### Paso 3: Subir tus Archivos

**Opción A: Por interfaz web (más fácil)**

1. En tu repositorio, haz clic en "uploading an existing file" O
2. Haz clic en "Add file" → "Upload files"
3. Arrastra tus carpetas:
   - `noticias/` (carpeta completa)
   - `posicionamiento/` (carpeta completa)
   - `README.md`
   - `POSICIONAMIENTOS_DETALLADO.md`
4. En "Commit message" escribe: "Proyecto inicial: noticias y posicionamientos"
5. Haz clic en "Commit changes"

**Opción B: Usar Git desde terminal (más profesional)**

```bash
# 1. Abre terminal en tu carpeta valentina_mejias
# 2. Inicializa Git
git init

# 3. Añade todos los archivos
git add .

# 4. Crea el primer commit
git commit -m "Proyecto inicial: portal de noticias y tutorial CSS"

# 5. Conecta con tu repositorio (reemplaza USERNAME)
git branch -M main
git remote add origin https://github.com/USERNAME/valentina_mejias.git

# 6. Sube los archivos
git push -u origin main
```

#### Paso 4: Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Haz clic en "Settings" (engranaje)
3. En el menú izquierdo, busca "Pages"
4. En "Source", selecciona:
   - Branch: `main`
   - Folder: `/ (root)`
5. Haz clic en "Save"
6. Espera 1-2 minutos
7. ¡Tu sitio estará en!
   ```
   https://tu-username.github.io/valentina_mejias/
   ```

#### Para Acceder a los Proyectos:
- **Noticias**: `https://tu-username.github.io/valentina_mejias/noticias/`
- **Posicionamiento**: `https://tu-username.github.io/valentina_mejias/posicionamiento/`

---

## OPCIÓN 2: NETLIFY

### ¿Por qué Netlify?
- ✅ Deploy automático desde GitHub
- ✅ Interfaz muy intuitiva
- ✅ Dominio personalizado gratuito
- ✅ HTTPS incluido
- ✅ Excelente para desarrollo

### Pasos:

1. **Sube a GitHub primero** (sigue Opción 1, pasos 1-3)

2. **Ve a Netlify**
   - Abre https://netlify.com
   - Haz clic en "Sign up"
   - Selecciona "GitHub"
   - Autoriza Netlify en GitHub

3. **Conecta tu Repositorio**
   - Haz clic en "New site from Git"
   - Selecciona GitHub
   - Elige el repositorio `valentina_mejias`
   - Haz clic en "Deploy site"

4. **Listo!**
   - Tu sitio estará en algo como: `https://xyz123.netlify.app/`
   - Los cambios en GitHub se despliegan automáticamente

---

## OPCIÓN 3: VERCEL

### ¿Por qué Vercel?
- ✅ La plataforma de Next.js
- ✅ Hosting súper rápido
- ✅ Deploy de un click
- ✅ Gratuito para proyectos estáticos

### Pasos:

1. **Ve a Vercel**
   - Abre https://vercel.com
   - Haz clic en "Sign Up"
   - Elige GitHub

2. **Selecciona tu Proyecto**
   - Autoriza Vercel en GitHub
   - Selecciona `valentina_mejias`
   - Haz clic en "Import"

3. **Configura y Deploy**
   - Deja las opciones por defecto
   - Haz clic en "Deploy"

4. **¡Hecho!**
   - URL: `https://valentina-mejias.vercel.app/`

---

## 🎯 COMPARATIVA RÁPIDA

| Característica | GitHub Pages | Netlify | Vercel |
|---|---|---|---|
| **Precio** | 100% Gratuito | 100% Gratuito | 100% Gratuito |
| **Facilidad** | Intermedia | Muy Fácil | Muy Fácil |
| **Dominio** | github.io | netlify.app | vercel.app |
| **Actualizaciones** | Manual/Git | Automática | Automática |
| **Mejor para** | Proyectos totales | Deploy rápido | Proyectos web |

**RECOMENDACIÓN**: Usa **GitHub Pages** si quieres tener control total y es tu primera vez. Es el estándar en la industria.

---

## 📋 LISTA DE VERIFICACIÓN PRE-PUBLICACIÓN

Antes de publicar, verifica:

- ✅ Carpeta `noticias/index.html` existe
- ✅ Carpeta `posicionamiento/index.html` existe
- ✅ CSS está en `assets/css/styles.css` de cada proyecto
- ✅ Imágenes están en `assets/img/` (aunque sean placeholders)
- ✅ HTML está bien formado (abre en navegador local)
- ✅ Todos los enlaces internos funcionan
- ✅ README.md está en la raíz

---

## 🔍 DESPUÉS DE PUBLICAR

### Verificar que Funcionó:

1. **Abre tu URL en el navegador** (de tu hosting elegido)
2. **Comprueba ambos proyectos:**
   - ¿Cargan las páginas?
   - ¿Se ven los estilos CSS?
   - ¿Se ven las imágenes? (si agregaste)
   - ¿Funcionan los links?

3. **Abre DevTools (F12)**
   - ¿Hay errores en la consola (rojo)?
   - ¿Faltan recursos (404)?

### Si Algo No Funciona:

**Problema: Las imágenes no cargan**
- Solución: Asegúrate que las rutas sean relativas: `assets/img/nombre.jpg`

**Problema: CSS no se ve**
- Solución: Verifica que `styles.css` esté en la ruta correcta

**Problema: Links rotos**
- Solución: Usa rutas relativas: `../posicionamiento/` NO `/posicionamiento/`

---

## 📱 DOMINIO PERSONALIZADO (OPCIONAL)

Si quieres un dominio personalizado `.com`, hay opciones como:
- **Namecheap**: dominios baratos (~$0.99 el primer año)
- **Google Domains**: administración fácil
- **Freenom**: dominios gratis (menos confiable)

Después conectas tu dominio al hosting en las configuraciones de DNS.

---

## 🚀 RESUMEN RÁPIDO - 3 PASOS

### Para GitHub Pages:
1. Crea repositorio en GitHub
2. Sube tus archivos
3. Activa Pages en Settings

### Para Netlify:
1. Conecta GitHub
2. Selecciona el repo
3. Haz clic en Deploy

### Para Vercel:
1. Ve a vercel.com
2. Importa desde GitHub
3. Listo

---

## ⚠️ IMPORTANTE

- **Versiones Correctas**: Asegúrate de subir HTML y CSS, no archivos temporales
- **Estructura**: Mantén la estructura de carpetas (no pongas todo en una carpeta)
- **Índices**: Cada carpeta debe tener su `index.html`
- **Rutas Relativas**: Usa siempre rutas relativas en HTML/CSS

---

## 💡 CONSEJO PROFESIONAL

Una vez publicado:
- Comparte el URL con tu profesor/compañeros
- Usa herramientas como Lighthouse (F12) para ver el score
- Considera agregar más contenido dinámico con JavaScript

**¡Tu proyecto está listo para ser visto por el mundo! 🌍✨**
