# 🗺️ Mapas Distritales del Perú

Colección completa de **1,800 mapas distritales** del Perú en alta calidad. Proyecto desarrollado por **BIM GIS con Luis**.

[![GitHub Pages](https://img.shields.io/badge/demo-live-brightgreen)](https://TU-USUARIO.github.io/bimgis-mapas-peru/)
[![YouTube](https://img.shields.io/badge/YouTube-BIM%20GIS%20con%20Luis-red)](https://www.youtube.com/@gisconluis6381)

## 📋 Descripción

Aplicación web interactiva que permite visualizar y descargar mapas de todos los distritos del Perú. Los mapas incluyen límites distritales oficiales en formato A4 de alta calidad.

## ✨ Características

- 🗺️ **1,800 mapas distritales** en formato WebP
- 📐 Formato A4 listo para imprimir
- 🎯 Límites oficiales y actualizados
- 🔍 Búsqueda jerárquica: Departamento → Provincia → Distrito
- 👁️ Vista previa antes de descargar
- 📱 Diseño responsive para móviles y tablets
- ⚡ Carga rápida y optimizada

## 🚀 Demo en Vivo

Visita la aplicación: [https://TU-USUARIO.github.io/bimgis-mapas-peru/](https://TU-USUARIO.github.io/bimgis-mapas-peru/)

## 📁 Estructura del Proyecto

```
bimgis-mapas-peru/
│
├── index.html              # Aplicación principal (HTML + CSS + JS)
├── README.md               # Este archivo
├── .gitignore             # Archivos ignorados por Git
│
├── data/                   # Datos geográficos
│   └── distritos.geojson  # GeoJSON con todos los distritos (1,800)
│
└── mapas/                  # Mapas en formato WebP (1,800 archivos)
    ├── Mapa-Distrito-ABANCAY-Provincia-ABANCAY-Departamento-APURIMAC-Peru-030101.webp
    ├── Mapa-Distrito-CUSCO-Provincia-CUSCO-Departamento-CUSCO-Peru-080101.webp
    └── ... (1,798 mapas más)
```

## 🛠️ Tecnologías

- **HTML5** - Estructura
- **CSS3** - Estilos responsive
- **JavaScript ES6+** - Lógica y procesamiento de datos
- **GeoJSON** - Formato de datos geográficos
- **WebP** - Formato optimizado para imágenes

## 📊 Datos Técnicos

- **Total de distritos**: 1,800
- **Departamentos**: 24 + Provincia Constitucional del Callao
- **Formato de mapas**: WebP (alta calidad, bajo peso)
- **Resolución**: A4 (210 x 297 mm)
- **Fuente de datos**: INEI - Instituto Nacional de Estadística e Informática

## 💻 Uso Local

### Opción 1: Con Live Server (VSCode)

1. Instala la extensión **Live Server** en VSCode
2. Abre el proyecto en VSCode
3. Clic derecho en `index.html` → **Open with Live Server**

### Opción 2: Con Python

```bash
# En la carpeta del proyecto:
python -m http.server 8000

# Abre en el navegador:
# http://localhost:8000
```

### Opción 3: Con Node.js

```bash
npx serve
```

## 🎯 Cómo Usar

1. Selecciona un **departamento** del menú desplegable
2. Elige una **provincia**
3. Selecciona el **distrito** deseado
4. Visualiza el mapa en la vista previa
5. Haz clic en **"Descargar Mapa"** para guardar la imagen

## 📝 Nomenclatura de Archivos

Los mapas siguen este formato:

```
Mapa-Distrito-[DISTRITO]-Provincia-[PROVINCIA]-Departamento-[DEPARTAMENTO]-Peru-[UBIGEO].webp
```

**Ejemplo:**
```
Mapa-Distrito-MIRAFLORES-Provincia-LIMA-Departamento-LIMA-Peru-150122.webp
```

Donde:
- **DISTRITO**: Nombre del distrito en mayúsculas
- **PROVINCIA**: Nombre de la provincia en mayúsculas
- **DEPARTAMENTO**: Nombre del departamento en mayúsculas
- **UBIGEO**: Código único de 6 dígitos (INEI)

## 🔗 Enlaces

- 🎥 [Canal de YouTube - BIM GIS con Luis](https://www.youtube.com/@gisconluis6381)
- 🌐 [Demo en Vivo](https://TU-USUARIO.github.io/bimgis-mapas-peru/)

## 📄 Licencia y Créditos

**© 2025 BIM GIS con Luis**

Mapas creados con QGIS utilizando datos oficiales del INEI.

---

## 🤝 Contribuciones

Si encuentras algún error o tienes sugerencias, siéntete libre de:
- Abrir un **Issue**
- Hacer un **Pull Request**
- Contactar a través del canal de YouTube

---

**Desarrollado con ❤️ por BIM GIS con Luis**