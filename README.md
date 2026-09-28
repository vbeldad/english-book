# English Book - Visor Interactivo 📖

Aplicación web interactiva para estudiar tu libro de inglés con navegación fluida y zoom.

## ¿Qué incluye?

- **24 páginas** del libro escaneadas
- **Navegación** fácil (botones, slider, flechas del teclado)
- **Zoom** flexible (50% a 300%)
- **Interfaz moderna** responsive
- **Atajos de teclado** para navegación rápida

## Atajos de Teclado ⌨️

| Atajo | Función |
|-------|---------|
| ← Flecha Izquierda | Página anterior |
| → Flecha Derecha | Página siguiente |
| `+` | Zoom in |
| `-` | Zoom out |
| `0` | Restablecer zoom |

## Cómo desplegar en GitHub Pages

### 1. Crea un repositorio en GitHub
```bash
git init
git add .
git commit -m "Initial commit: English book viewer"
git branch -M main
git remote add origin https://github.com/vbeldad/english-book.git
git push -u origin main
```

### 2. Activa GitHub Pages
1. Ve a **Settings** del repositorio
2. Busca **Pages** en el menú izquierdo
3. En "Source", selecciona **main** (rama)
4. Click en **Save**

### 3. ¡Listo!
Tu app estará disponible en: `https://vbeldad.github.io/english-book/`

## Estructura del proyecto

```
english-book/
├── index.html          (La aplicación)
├── page-000.jpg        (Página 1)
├── page-001.jpg        (Página 2)
├── ...
├── page-023.jpg        (Página 24)
└── README.md           (Este archivo)
```

## Características técnicas

- ✅ Funciona offline una vez descargado
- ✅ Totalmente responsivo (funciona en móvil, tablet, escritorio)
- ✅ Sin dependencias externas
- ✅ Carga rápida de páginas
- ✅ Optimizado para lectura

## Tamaño

- HTML: ~11 KB
- Imágenes: ~18 MB (24 páginas JPEG optimizadas)
- Total: ~18 MB

---

Creado con ❤️ para estudiar inglés de forma interactiva.
