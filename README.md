# 📖 EasyReader
> **Asistente de Lectura Inteligente con OCR en Tiempo Real**

<div align="center">

[![Abrir App](https://img.shields.io/badge/🚀%20ABRIR%20EASYREADER-Ejecutar%20en%20Navegador-00cec9?style=for-the-badge&logoColor=white)](https://csav20.github.io/easyreader/)

[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Tesseract.js](https://img.shields.io/badge/OCR-Tesseract.js%20v5-00cec9.svg?style=for-the-badge)](https://tesseract.projectnaptha.com/)
[![Vanilla JS](https://img.shields.io/badge/JS-Vanilla%20ES6+-6c5ce7.svg?style=for-the-badge)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-181717?style=for-the-badge&logo=github)](https://csav20.github.io/easyreader/)

</div>

---

EasyReader es una aplicación web progresiva que utiliza reconocimiento óptico de caracteres (OCR) para extraer texto de imágenes capturadas en tiempo real desde la cámara de tu dispositivo. Diseñada con una interfaz moderna, oscura y responsive, es perfecta para leer documentos, carteles, menús o cualquier texto impreso.

> ⚠️ **Requiere HTTPS y permiso de cámara.** Funciona directamente desde el botón de arriba (GitHub Pages).

---

## ✨ Características

| Característica | Descripción |
|---|---|
| 📷 **Escaneo en Tiempo Real** | Captura y procesa texto desde la cámara del dispositivo |
| 🌐 **Soporte Multilenguaje** | Español (`spa`) — extensible a otros idiomas |
| ⚡ **Modo Sección / Página Completa** | Escaneo rápido de áreas específicas o documentos completos |
| 🔄 **Auto-Escaneo Inteligente** | Escaneo automático con intervalos configurables (2s, 4s, 6s, 8s) |
| 🔊 **Lectura en Voz Alta** | Text-to-Speech integrado para escuchar el texto reconocido |
| 📋 **Copiar y Exportar** | Copia todo el historial de texto al portapapeles |
| 🔦 **Linterna y Cambio de Cámara** | Control de hardware para mejor experiencia en baja luz |
| 🎨 **Dark Mode** | Diseño optimizado para reducir fatiga visual |
| 📱 **Mobile-First** | Responsive con soporte completo para móviles |

---

## 🚀 Uso Rápido

### Opción 1: Desde el navegador (recomendado)

<div align="center">

**[👉 https://csav20.github.io/easyreader/](https://csav20.github.io/easyreader/)**

</div>

No requiere instalación. Solo abre el enlace, acepta el permiso de cámara y escanea.

### Opción 2: Local

```bash
git clone https://github.com/Csav20/easyreader.git
cd easyreader
python -m http.server 8000
# Abrir http://localhost:8000
```

### 🔐 Permisos requeridos
- 📷 **Cámara**: Para capturar imágenes en tiempo real
- 📋 **Portapapeles**: Para la función de copiar texto

> ⚠️ Las APIs de cámara requieren **HTTPS** o **localhost**. El botón de arriba ya usa HTTPS vía GitHub Pages.

---

## 🛠 Stack Tecnológico

```
📦 Frontend
├── HTML5 Semántico
├── CSS3 con Custom Properties (Dark Mode nativo)
├── JavaScript Vanilla ES6+
├── Tesseract.js v5 (OCR en el navegador, sin servidor)
└── Web APIs: MediaDevices, SpeechSynthesis, Clipboard API

🚀 Sin dependencias externas pesadas · Sin backend · Sin instalación
```

---

## ⌨️ Atajos de Teclado

| Tecla | Acción |
|---|---|
| `Espacio` | Escanear sección |
| `Ctrl + A` | Activar/Desactivar auto-escaneo |
| `Ctrl + L` | Leer último texto en voz alta |

---

## 🌐 Compatibilidad

| Navegador | Soporte |
|---|---|
| Chrome 80+ | ✅ Completo |
| Firefox 75+ | ✅ Completo |
| Safari 14+ (iOS 14.5+) | ✅ Completo |
| Edge 80+ | ✅ Completo |

> 📱 Optimizado para Android 10+ e iOS 14.5+

---

## 📁 Estructura

```
easyreader/
├── index.html   ← Aplicación completa (self-contained)
└── README.md    ← Esta documentación
```

---

## 🗺️ Roadmap

- [ ] 🧠 Preprocesamiento inteligente (binarización adaptativa, deskew)
- [ ] 📐 Detección automática de documentos con OpenCV.js
- [ ] ⚡ OCR diferencial (evitar reprocesar texto sin cambios)
- [ ] 🌍 Traducción automática integrada
- [ ] 📄 Exportación a PDF
- [ ] 🔐 Modo offline con Service Worker

---

## 📄 Licencia

MIT © 2024 [Claudio Abarca Vargas](https://github.com/Csav20)

---

<div align="center">

[![Abrir App](https://img.shields.io/badge/🚀%20ABRIR%20EASYREADER-csav20.github.io%2Feasyreader-00cec9?style=for-the-badge)](https://csav20.github.io/easyreader/)

Hecho con ❤️ para hacer la lectura accesible para todos.

</div>
