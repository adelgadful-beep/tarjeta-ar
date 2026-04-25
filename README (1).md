# 🃏 Tarjeta AR — Arturo Delgado
**Servicios Digitales e Impresión · Guapiles, Limón, CR**

---

## 📁 Estructura del repositorio

```
/
├── tarjeta-ar.html          ← Experiencia de Realidad Aumentada (página principal)
├── tarjeta-imprimible.html  ← Tarjeta de presentación con QR para imprimir
├── model.glb                ← Tu avatar 3D
├── instagram_png_.jpg       ← Logo de Instagram
├── whatapp_png_.png         ← Logo de WhatsApp
└── README.md                ← Este archivo
```

> ⚠️ **IMPORTANTE:** Los 4 archivos de assets (`.glb`, `.jpg`, `.png`) deben estar
> en la misma carpeta raíz que los archivos HTML. Vercel los sirve automáticamente.

---

## 🚀 Publicar en Vercel desde GitHub (GRATIS)

### Paso 1 — Crear repositorio en GitHub

1. Ve a [github.com/new](https://github.com/new)
2. Nombre del repo: `tarjeta-ar` (o el que prefieras)
3. Visibilidad: **Public** ✅ (necesario para Vercel gratis)
4. Haz clic en **Create repository**

### Paso 2 — Subir los archivos

**Opción A — Desde el navegador (más fácil):**
1. En tu repo vacío, haz clic en **"uploading an existing file"**
2. Arrastra los 5 archivos de una vez:
   - `tarjeta-ar.html`
   - `tarjeta-imprimible.html`
   - `model.glb`
   - `instagram_png_.jpg`
   - `whatapp_png_.png`
3. Escribe un mensaje como `"Primera versión tarjeta AR"`
4. Clic en **Commit changes**

**Opción B — Con Git (desde terminal):**
```bash
git init
git add .
git commit -m "Primera versión tarjeta AR"
git remote add origin https://github.com/TU_USUARIO/tarjeta-ar.git
git push -u origin main
```

### Paso 3 — Conectar con Vercel

1. Ve a [vercel.com](https://vercel.com) e inicia sesión con tu cuenta de **GitHub**
2. Clic en **"Add New Project"**
3. Selecciona el repo `tarjeta-ar`
4. En configuración:
   - **Framework Preset:** `Other`
   - **Root Directory:** `/` (dejar vacío)
   - **Build Command:** (dejar vacío)
   - **Output Directory:** (dejar vacío)
5. Clic en **Deploy** 🚀

Vercel te da una URL como:
```
https://tarjeta-ar.vercel.app
```

### Paso 4 — Actualizar la URL del QR

Abre `tarjeta-imprimible.html` y cambia esta línea:
```javascript
const AR_URL = "https://adelgadful.vercel.app/tarjeta-ar.html";
```
Por:
```javascript
const AR_URL = "https://tarjeta-ar.vercel.app/tarjeta-ar.html";
```
Luego haz commit y Vercel se actualiza automáticamente.

### Paso 5 — Imprimir el Marcador Hiro

Descarga e imprime el marcador:
👉 https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png

- Tamaño recomendado: **3×3 cm** mínimo
- Ponlo en tu tarjeta física (en el espacio en blanco del QR o al reverso)
- Fondo blanco, buena impresión

---

## 🔗 Links de tu tarjeta

| Canal | URL |
|---|---|
| 🌐 Web AR | https://adelgadful.vercel.app/tarjeta-ar.html |
| 📱 WhatsApp | https://wa.me/50686099810 |
| 📸 Instagram | https://www.instagram.com/adelgadful_/ |
| 📧 Email | adelgadful@gmail.com |
| 🌍 Web | https://adelgadful.vercel.app/ |

---

## 🛠 Cómo actualizar tu tarjeta

Cada vez que edites un archivo y lo subas a GitHub, **Vercel lo publica automáticamente** en segundos. No necesitas hacer nada más.

---

*Creado con A-Frame + AR.js — 100% gratuito*
