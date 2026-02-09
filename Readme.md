# 📊 Smart Analytics Tracker

Sistema avanzado de tracking de interacciones del usuario construido con JavaScript vanilla y APIs modernas del DOM.

Creado por **Irina Ichim** ([Irina-Ichim](https://github.com/Irina-Ichim)), cofundadora de FemCoders Club, para el post: *"Manipulación del DOM como una Ingeniera"*

---

## 🎯 Objetivo del Proyecto

Demostrar manipulación avanzada del DOM en JavaScript, sin frameworks ni dependencias externas.

![Demo del Smart Analytics Tracker](assets/manipulacion-dom.png)

---

## 📚 Conceptos Técnicos Cubiertos

- Event Delegation
- IntersectionObserver
- MutationObserver
- Custom Events (EventBus)
- Performance Optimization
- Rage Clicks, Heatmap, Scroll Analytics

---

## 🎨 Funcionalidades Principales

- Click Tracking + Heatmap
- Visibility Tracking
- Scroll Analytics
- Rage Click Detection

---

## 💻 Tecnologías Utilizadas

- JavaScript ES6+ (Vanilla)
- ES Modules
- Web APIs: IntersectionObserver, MutationObserver, Performance API, Canvas API
- CSS3, HTML5
- **Dependencias:** 0

---

## 🚀 Quick Start

### Demo Interactiva

```bash
cd demo
python3 -m http.server 8000
# Abre http://localhost:8000
```

### Uso en tu proyecto

```javascript
import { TrackerEngine, ClickCollector } from './src/index.js';
const tracker = new TrackerEngine();
tracker.use(new ClickCollector());
tracker.start();
// Exportar métricas
tracker.export('analytics.json');
```

---

## 📝 Ejemplo Mínimo

```javascript
import { TrackerEngine, ClickCollector } from './src/index.js';
const tracker = new TrackerEngine();
tracker.use(new ClickCollector());
tracker.start();
setTimeout(() => {
  tracker.export('analytics.json');
}, 30000);
```

---

## 📊 Métricas del Proyecto

- ~2,500 líneas de JavaScript
- ~500 líneas de CSS
- ~300 líneas de HTML
- 100% documentado

---

## 💜 FemCoders Club

Este proyecto demuestra que las desarrolladoras pueden:
- Construir sistemas complejos desde cero
- Dominar APIs avanzadas del navegador
- Aplicar patrones de diseño profesionales
- Optimizar para performance
- Crear código mantenible y escalable

**Mensaje:** No necesitas frameworks para hacer cosas increíbles. JavaScript vanilla + conocimiento profundo del DOM = Superpoderes 🦸‍♀️

---

**Creado por Irina Ichim** ([Irina-Ichim](https://github.com/Irina-Ichim)), cofundadora de FemCoders Club.

---

## 🌐 Comunidad FemCoders Club

- Instagram: [@femcoders_club](https://www.instagram.com/femcoders_club/)
- Slack: [Unirse a Slack](https://communityinviter.com/apps/femcodersclub/femcoders-club)
