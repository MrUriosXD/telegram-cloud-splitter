# 📦 Telegram Cloud Splitter (No Oficial)

![Licencia](https://img.shields.io/badge/licencia-MIT-blue.svg)
![Estado](https://img.shields.io/badge/estado-activo-brightgreen.svg)
![Arquitectura](https://img.shields.io/badge/arquitectura-100%25%20Client--Side-orange.svg)

**Telegram Cloud Splitter** es una aplicación web cliente (100% independiente) diseñada para fragmentar archivos de gran tamaño directamente en tu navegador, adaptándolos a los límites de almacenamiento de almacenamiento en la nube de Telegram (Telegram Cloud).

---

## 🚀 Características Clave

- **🔒 Privacy First (Procesamiento Local):** Todo el proceso se ejecuta localmente usando el motor de JavaScript y el objeto `Blob` / `File API` de tu navegador. Tu archivo jamás se sube a ningún servidor.
- **⚡ Sin límite de tamaño de archivo:** Puedes procesar ficheros de cualquier dimensión (mientras el hardware de tu navegador lo permita).
- **⚙️ Soporte para Telegram Free y Premium:**
  - **Telegram Free:** Divide automáticamente en partes de **2.000 MB** (2 GB).
  - **Telegram Premium:** Divide automáticamente en partes de **4.000 MB** (4 GB).
- **🗂️ Compatibilidad de Nomenclatura Estándar:**
  - **WinRAR:** Salida tipo `.part1.rar`, `.part2.rar`, etc.
  - **7-Zip:** Salida tipo `.7z.001`, `.7z.002`, etc.
- **📱 Interfaz Neumórfica & Responsive:** Diseñada con estilos modernos inspirados en la interfaz de Telegram con soporte para arrastrar y soltar (Drag & Drop).

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3:** Variables CSS, layouts flexbox/grid y animaciones suaves con diseño adaptativo.
- **JavaScript ES6+:** Manipulación nativa de archivos binarios utilizando `File.slice()` y URLs de objetos (`URL.createObjectURL`).
- **Google Fonts:** Tipografías *Plus Jakarta Sans* y *JetBrains Mono*.

---

## 📖 Modo de Uso

1. **Abrir la herramienta:** Abre el archivo `telegram_cloud_splitter.html` en cualquier navegador moderno (Chrome, Firefox, Edge, Brave, Safari).
2. **Seleccionar Opciones:**
   - **Plan:** Elige entre límite de 2 GB (*Gratuito*) o 4 GB (*Premium*).
   - **Formato:** Selecciona la nomenclatura deseada (*WinRAR* o *7-Zip*).
3. **Cargar Archivo:** Arrastra tu documento a la zona designada o haz clic para seleccionarlo.
4. **Revisar Estructura:** La aplicación calculará la cantidad exacta de partes y el peso de cada tomo.
5. **Iniciar Partición:** Haz clic en **"Iniciar Partición y Descargas"**. Los archivos fragmentados comenzarán a descargarse automáticamente uno a uno.

---

## 📂 ¿Cómo Recomponer las Partes Descargadas?

Una vez descargadas las partes y guardadas en tu equipo:

### Para formato WinRAR (`.part1.rar`):
1. Asegúrate de tener todas las partes descargadas en la misma carpeta.
2. Haz clic derecho sobre el archivo `.part1.rar` y selecciona **Extraer aquí** con WinRAR o un descompresor compatible.

### Para formato 7-Zip (`.7z.001`):
1. Coloca todos los tomos (`.7z.001`, `.7z.002`, etc.) en el mismo directorio.
2. Abre 7-Zip o PeaZip, selecciona la primera parte (`.7z.001`) y haz clic en **Extraer**.

---

## ⚠️ Descargo de Responsabilidad (Disclaimer)

> **Nota Importante:** Esta aplicación es un desarrollo independiente y no oficial. **No tiene afiliación, patrocinio ni vinculación formal con Telegram LLC.** Es una utilidad basada en navegador que simplemente facilita el fraccionamiento de archivos para cumplir con las directrices de tamaño máximo permitidas por la plataforma.

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Siéntete libre de modificarlo o contribuir.