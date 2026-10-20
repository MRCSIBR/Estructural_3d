# 🏗️ Visor 3D — Techo Inclinado 4×3 m

Visualizador 3D paramétrico e interactivo de una estructura metálica unidual (techo a un agua) fabricada en **PTR 100×100 mm** con cubierta de **chapa trapezoidal de zinc (T-101)**.

Desarrollado con **Three.js** (sin librerías locales, 100% en el navegador).

---

## 🌐 Demo en vivo

👉 **[Ver proyecto online](https://mrcsibr.github.io/Estructural_3d/)**  
*(Reemplaza con tu usuario y nombre de repositorio)*

---

## ✨ Características

- **Paramétrico en tiempo real:**
  - Ajuste de altura para columnas delanteras (frente) y traseras (fondo).
  - Cálculo dinámico de pendiente (% y grados).
  - Cómputo de materiales (BOM) actualizado al instante.
- **Visualización interactiva:**
  - Despiece vertical / vista explosionada de la chapa.
  - Control de opacidad y visibilidad de la cubierta.
  - Perfiles PTR huecos reales con bordes curvados y tornillería autoperforante.
- **Materiales PBR procedurales:** Acero al carbono, zinc galvanizado y piso de hormigón sin texturas externas pesadas.

---

## 🎮 Controles de Cámara

| Acción | Control |
|---|---|
| **Rotar** | Clic izquierdo + arrastrar |
| **Desplazar (Pan)** | Clic derecho + arrastrar |
| **Zoom** | Rueda del mouse |

---

## 🛠️ Tecnologías

- **HTML5 / CSS3** (Interfaz responsiva moderna tipo glassmorphism).
- **JavaScript (ES Modules)**.
- **Three.js r160** (vía CDN / importmap).
- **OrbitControls** & **RoomEnvironment**.

---

## 🚀 Uso Local

No requiere Node.js ni instalación de paquetes:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git
