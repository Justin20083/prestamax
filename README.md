# Leolyt 💚

PWA completa para gestión de préstamos con estilo **Material You 3 Expressive**.

## 🔗 Enlace
**https://github.com/Justin20083/leolyt**

## ✨ Características

### 📱 App Completa
- **Dashboard** con estadísticas animadas y gráfico de ingresos
- **Clientes** con búsqueda, filtros y CRUD completo
- **Préstamos** con seguimiento de progreso y estados
- **Pagos** con historial y tipos (cobros/pagos)
- **Calendario** con eventos de vencimiento
- **Asistente AI** con respuestas contextuales
- **Reportes** con gráficos y rankings
- **Ajustes** con perfil, moneda, tasa de interés

### 🎨 Material You 3 Expressive
- Superficies tonales verde (`#C62828`)
- Esquinas ultra-redondeadas (28px cards, pills)
- Spring curves con overshoot
- Animaciones de scroll reveal
- Active compression en todos los botones
- Zero borders/shadows (tonal differentiation)

### 📲 PWA Features
- Offline con Service Worker
- Installable en手机
- Safe-area insets para notch
- Touch-optimized (44px+ targets)

## 🚀 Uso

1. Abre `index.html` en tu navegador
2. Ingresa tu nombre para empezar
3. Agrega clientes, préstamos y pagos
4. Usa el asistente AI para análisis

## 🛠️ Tech Stack

- **HTML/CSS/JS** vanilla (sin frameworks)
- **Google Fonts** Inter (400-900)
- **SVG icons** Lucide-style
- **Canvas API** para gráficos
- **localStorage** para persistencia
- **Service Worker** para offline

## 📁 Estructura

```
leolyt/
├── index.html        ← App completa (single-file)
├── manifest.json     ← PWA manifest
├── sw.js             ← Service Worker
├── icon-192.png      ← App icon 192x192
└── icon-512.png      ← App icon 512x512
```

## 🎨 Personalización

El color primary se puede cambiando la variable CSS:
```css
--p:#C62828;  /* Cambia este valor */
```

## 📄 Licencia

MIT