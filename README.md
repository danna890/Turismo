# 🌎 Proyecto COLOMBIA  

Este proyecto consiste en un **sitio web** que reúne información visual y descriptiva de diferentes departamentos de Colombia. Cada región cuenta con su propia página en formato **HTML**, acompañada de imágenes representativas, con el fin de **divulgar la riqueza cultural, natural y turística del país**.  

El sitio está pensado para ser simple de usar y fácil de extender, de manera que pueda crecer con la adición de nuevos departamentos y recursos.  

---

## 📂 Estructura del proyecto

COLOMBIA/
│── amazonas.html # Página dedicada al Amazonas
│── antioquia.html # Página dedicada a Antioquia
│── meta.html # Página dedicada al Meta
│── mapa.html # Página general del mapa de Colombia
│── ANTIOQUIA-1280x720-1.jpg # Imagen de soporte para la página de Antioquia
│── *.jpg / *.png # Resto de imágenes para ilustrar el contenido
│── .git/ # Carpeta de control de versiones Git

Cada archivo `.html` funciona de manera independiente, pero puede conectarse a través de enlaces de navegación para ofrecer una experiencia más fluida al usuario.  
  

---

## ✨ Características principales

- 🌿 **Amazonas**: página con imágenes de la selva, gastronomía local (como el pescado de río, casabe de yuca, juane amazónico, copoazú, camu camu, etc.) y atractivo turístico.  
- 🏞️ **Antioquia**: página dedicada a la cultura paisa y paisajes representativos.  
- 🌾 **Meta**: página enfocada en los Llanos Orientales, con su riqueza natural y cultural.  
- 🗺️ **Mapa principal**: archivo **mapa.html** que funciona como punto de inicio para acceder a las demás regiones.  
- 🖼️ **Galería de imágenes**: las páginas están enriquecidas con fotografías (.jpg y .png) para ilustrar el contenido.  

---

## 🛠️ Tecnologías utilizadas

- **HTML5** → para la estructura de las páginas.  
- **CSS (si está incrustado en los .html)** → para la apariencia y estilos del sitio.  
- **Imágenes en .jpg y .png** → como contenido multimedia de soporte.   

---

## ⚙️ Instalación y uso

1. **Clonar el repositorio** (si está en GitHub) o descomprimir la carpeta *COLOMBIA*:  
   ```bash
   git clone <url-del-repo>
Abrir los archivos HTML en un navegador (doble clic o arrastrando el archivo al navegador):

mapa.html → Página principal del sitio.

amazonas.html → Página del Amazonas.

antioquia.html → Página de Antioquia.

meta.html → Página del Meta.

(Opcional) Usar un servidor local para navegación más fluida entre páginas:

bash
Copiar código
cd COLOMBIA
python -m http.server 8000
Luego abrir en el navegador: http://localhost:8000

📌 Próximas mejoras
🔗 Implementar navegación común (menú o barra superior) entre todas las páginas.

📝 Agregar descripciones detalladas de gastronomía, cultura, fauna y flora de cada región.

📱 Incluir un diseño responsivo con CSS para móviles y tabletas.

☁️ Publicar el sitio en GitHub Pages o en un servidor web.

🌍 Extender el proyecto con más departamentos de Colombia.

