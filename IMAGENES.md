# 📸 Imágenes del Proyecto Café Aroma

## Resumen de Imágenes Agregadas

Este documento detalla todas las imágenes que se han integrado al sitio web de Café Aroma usando el servicio gratuito de Unsplash.

---

## 🏠 Página Principal (index.html)

### Banner Hero Principal

- **Ubicación**: Sección hero de la página principal
- **Imagen**: Cafetería con ambiente cálido
- **URL**: `https://images.unsplash.com/photo-1511920170033-f8396924c348`
- **Efecto**: Overlay oscuro con gradiente para mejorar legibilidad del texto

### Productos Favoritos (3 imágenes)

1. **Espresso Intenso**

   - URL: `https://images.unsplash.com/photo-1510591509098-f4fdc6d0ff04`
   - Descripción: Shot de espresso en taza blanca

2. **Latte Cremoso**

   - URL: `https://images.unsplash.com/photo-1461023058943-07fcbe16d735`
   - Descripción: Latte con arte latte (diseño en espuma)

3. **Croissant Francés**
   - URL: `https://images.unsplash.com/photo-1555507036-ab1f4038808a`
   - Descripción: Croissants recién horneados y dorados

---

## 👥 Página Nosotros (about.html)

### Imagen "Nuestra Cafetería"

- **Ubicación**: Sección de historia
- **Imagen**: Interior de cafetería moderna y acogedora
- **URL**: `https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb`
- **Efecto**: Overlay semitransparente para el texto

---

## 🖼️ Página Galería (gallery.html)

### Sección: Nuestros Cafés (4 imágenes)

1. **Espresso Perfecto**

   - URL: `https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd`
   - Descripción: Taza de espresso sobre mesa de madera

2. **Arte Latte**

   - URL: `https://images.unsplash.com/photo-1572442388796-11668a67e53d`
   - Descripción: Latte con diseño artístico en la espuma

3. **Capuchino Cremoso**

   - URL: `https://images.unsplash.com/photo-1517487881594-2787fef5ebf7`
   - Descripción: Capuchino perfectamente preparado

4. **Cold Brew**
   - URL: `https://images.unsplash.com/photo-1517668808822-9ebb02f2a0e6`
   - Descripción: Café frío con hielo en vaso alto

### Sección: Repostería Artesanal (4 imágenes)

1. **Croissants Recién Horneados**

   - URL: `https://images.unsplash.com/photo-1530610476181-d83430b64dcd`
   - Descripción: Croissants hojaldrados dorados

2. **Variedad de Pasteles**

   - URL: `https://images.unsplash.com/photo-1509440159596-0249088772ff`
   - Descripción: Selección de pasteles y dulces

3. **Cheesecake Especial**

   - URL: `https://images.unsplash.com/photo-1533134242116-8a3d0d5d87f5`
   - Descripción: Porción de cheesecake cremoso

4. **Galletas Caseras**
   - URL: `https://images.unsplash.com/photo-1558961363-fa8fdf82db35`
   - Descripción: Galletas de chocolate chip

### Sección: Nuestro Espacio (4 imágenes)

1. **Ambiente Acogedor**

   - URL: `https://images.unsplash.com/photo-1445116572660-236099ec97a0`
   - Descripción: Interior cálido de cafetería

2. **Barra de Café**

   - URL: `https://images.unsplash.com/photo-1442512595331-e89e73853f31`
   - Descripción: Barra con máquina de espresso profesional

3. **Áreas de Estar**

   - URL: `https://images.unsplash.com/photo-1493857671505-72967e2e2760`
   - Descripción: Mesas y sillas acogedoras

4. **Terraza Exterior**
   - URL: `https://images.unsplash.com/photo-1554118811-1e0d58224f24`
   - Descripción: Espacio exterior con mesas al aire libre

---

## 🔧 Implementación Técnica

### Método Utilizado

Todas las imágenes se implementaron usando **inline styles** con la propiedad `background-image` de CSS.

### Parámetros de URL

- `w=600` o `w=1920`: Ancho optimizado para web
- `q=80`: Calidad de imagen al 80% (balance perfecto entre calidad y velocidad)

### Propiedades CSS Aplicadas

```css
background-image: url("...");
background-size: cover;
background-position: center;
```

---

## ✨ Ventajas de las Imágenes Usadas

### ✅ Gratis y Legales

- Todas las imágenes provienen de Unsplash
- Licencia gratuita para uso comercial
- No requiere atribución (aunque es recomendable)

### ✅ Alta Calidad

- Fotografías profesionales
- Resolución optimizada para web
- Colores vibrantes y composiciones atractivas

### ✅ CDN de Unsplash

- Carga rápida desde su red de distribución
- Optimización automática
- Disponibilidad garantizada

---

## 🔄 Cómo Reemplazar las Imágenes

Si deseas usar imágenes propias en el futuro:

### Opción 1: Imágenes Locales

1. Guarda tus imágenes en la carpeta `images/`
2. Cambia las URLs en el HTML:
   ```html
   style="background-image: url('images/tu-imagen.jpg');"
   ```

### Opción 2: Otras URLs

1. Sube tus imágenes a un servicio de hosting (Cloudinary, ImgBB, etc.)
2. Reemplaza las URLs de Unsplash con tus URLs

### Ejemplo de Reemplazo

```html
<!-- Antes -->
<div style="background-image: url('https://images.unsplash.com/photo-xxx');">
  <!-- Después -->
  <div style="background-image: url('images/mi-cafe.jpg');"></div>
</div>
```

---

## 📊 Estadísticas del Proyecto

- **Total de imágenes**: 16 imágenes
- **Páginas con imágenes**: 3 (index.html, about.html, gallery.html)
- **Tamaño promedio**: ~100-150 KB por imagen (optimizadas)
- **Tiempo de carga estimado**: < 2 segundos con conexión normal

---

## 🎨 Efectos y Overlays

### Hero Banner

- Gradiente oscuro sobre la imagen para mejorar contraste
- Texto blanco legible sobre cualquier parte de la imagen

### Galería

- Overlay aparece al hacer hover
- Transición suave y elegante
- Información descriptiva visible

### Cards de Productos

- Imágenes con `background-size: cover` para ajuste perfecto
- Sin overlays para mostrar producto completo
- Bordes redondeados para diseño moderno

---

## 💡 Recomendaciones Futuras

### Para Producción Real

1. **Fotografía profesional propia**

   - Contratar fotógrafo profesional
   - Capturar productos reales de la cafetería
   - Mantener consistencia visual

2. **Optimización**

   - Comprimir imágenes (usar TinyPNG o similar)
   - Implementar lazy loading
   - Usar formatos modernos (WebP)

3. **Responsive**
   - Crear versiones en diferentes resoluciones
   - Usar `srcset` para imágenes adaptativas
   - Optimizar para dispositivos móviles

---

## 📝 Créditos

**Fuente de imágenes**: [Unsplash](https://unsplash.com)  
**Licencia**: Unsplash License (uso gratuito)  
**Fotógrafos**: Diversos fotógrafos profesionales de Unsplash

---

## ✅ Checklist de Imágenes

- [x] Banner principal hero
- [x] 3 productos favoritos en inicio
- [x] Imagen cafetería en página Nosotros
- [x] 4 imágenes de cafés en galería
- [x] 4 imágenes de repostería en galería
- [x] 4 imágenes del espacio en galería

**Total: 16 imágenes implementadas** ✨

---

¡Todas las imágenes están listas y funcionando! 🎉☕
