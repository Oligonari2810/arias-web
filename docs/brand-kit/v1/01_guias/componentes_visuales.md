# Componentes y patrones visuales — Arias Group Caribe

Este documento describe los patrones visuales que usa la web actual y que deben replicarse en cualquier pieza nueva (Instagram, banners, presentaciones, firmas email, etc.) para mantener coherencia de marca.

---

## 1. Header / Hero de sección

Patrón dominante en toda la web. Se usa como primera pantalla.

**Estructura:**
- Imagen de fondo a pantalla completa (foto arquitectónica)
- Overlay navy degradado (de 40% a 90% de arriba abajo)
- Contenido alineado abajo-izquierda
- 3 niveles tipográficos:
  1. Kicker (Inter 600, mayúsculas, letter-spacing amplio, color sky-pale)
  2. Título Fraunces grande (400/500, color blanco, cursivas en acento)
  3. Subtítulo (Inter 400, color sky-pale)

**Aplicación fuera de web:**
- Banner Instagram: misma foto con overlay, título Fraunces
- Portada presentación: idéntica estructura
- Email header: versión simplificada

---

## 2. Grid editorial asimétrico

Patrón para mostrar colecciones (productos, servicios, sistemas).

**Estructura:**
- Grid de 12 columnas con tiles de tamaños desiguales
- Tile grande (7 columnas) + tile mediano (5 columnas) en fila 1
- 3 tiles iguales (4 columnas cada uno) en fila 2
- Cada tile: foto de fondo + overlay navy + número (Inter mono) + título (Fraunces) + subtítulo corto

**Cuándo usarlo:** presentación de portafolio, galerías, menús visuales.

---

## 3. Sección con foto de fondo a pantalla completa + overlay

Patrón para momentos narrativos fuertes (manifiesto, "Europa al trópico", CTAs).

**Estructura:**
- Foto a `object-cover`
- Overlay navy del 85% (casi sólido)
- Contenido tipográfico grande en centro

**Cuándo usarlo:** momentos de quiebre narrativo, diferenciación competitiva, CTAs importantes.

---

## 4. Pull quote (claim de marca)

Patrón para frases manifiesto.

**Estructura:**
- Centrado horizontal
- Texto grande Fraunces 400 (28–32px)
- Cursiva en la palabra-ancla
- Abajo: atribución en Inter 600 mayúsculas con letter-spacing amplio
- Sin comillas decorativas (es claim, no cita)

---

## 5. Bloque de números / estadísticas

Patrón para comunicar datos duros.

**Estructura:**
- Fondo navy sólido
- Grid de 4 columnas
- Cada columna: línea fina blue arriba + número gigante Fraunces + descripción corta Inter

**Reglas:**
- Máximo 4 números por bloque (ritmo visual)
- Números con Fraunces 400, tamaño 60–72px
- Descripciones en 2 líneas máximo

---

## 6. Botones / CTAs

**Primario (acción principal):**
- Fondo navy `#1A3557`
- Texto blanco Inter 600
- Padding generoso (32px horizontal, 16–20px vertical)
- Sin bordes redondeados (esquinas rectas — proyecta seriedad técnica)
- Hover: cambia a blue `#2563A8`

**Secundario:**
- Transparente con borde navy
- Texto navy Inter 600
- Hover: invierte colores (fondo navy, texto blanco)

**CTA WhatsApp (siempre con icono):**
- Icono SVG WhatsApp a la izquierda del texto
- Texto: "Escribir por WhatsApp" o "Enviar por WhatsApp"

**Reglas:**
- Máximo 2 CTAs visibles por sección
- En pantalla pequeña (móvil), los CTAs se apilan verticalmente
- Nunca usar botones con color dorado o acentos no permitidos

---

## 7. Tarjetas editoriales (dos promesas / Caribe)

Patrón para explicar conceptos con imagen.

**Estructura:**
- Card con aspect ratio 5:4 o 4:3
- Imagen de fondo con overlay navy
- Etiqueta superior (categoría / tipo — Inter 600 mayúsculas)
- Título Fraunces 500
- Párrafo descriptivo Inter 400
- Opcional: badge en esquina ("Único en RD")

---

## 8. Separadores y jerarquía

- **Línea horizontal fina** sobre bloques numéricos: `border-top: 1px solid #2563A8` (blue)
- **Kicker siempre** antes de título de sección — da ritmo
- **Espaciado vertical generoso** entre secciones: 96–128px desktop, 64–80px móvil
- **Grid max-width:** 1280px (`max-w-7xl`) — nunca full-bleed salvo heros con foto

---

## 9. Iconografía

- **WhatsApp:** siempre usar el SVG oficial (verde en canal directo, blanco sobre navy en CTAs)
- **Redes sociales:** (pendiente handles oficiales)
- **NO usar emojis** en copy corporativo
- **SÍ usar emojis** ocasionalmente en redes sociales cuando aporten claridad visual (no decoración)

---

## 10. Fotografía — criterio

**Qué SÍ buscamos:**
- Arquitectura moderna, líneas rectas
- Fachadas, detalles constructivos
- Obras reales (cuando tengamos portafolio)
- Paisajes tropicales cuando contexto lo pide
- Color dominante neutro o cálido suave

**Qué NO usamos:**
- Stock fotos obvias de "gente sonriendo con casco"
- Imágenes con mucho color saturado
- Fotos de obra en polvo sin estética
- Imágenes verticales genéricas
- Handshakes, meetings con laptops — cliché B2B

**Referencias visuales:**
- Foster + Partners
- Herzog & de Meuron
- Rockwool Building Solutions
- Kingspan
- Revistas Arquitectura Viva, Dezeen, Domus
