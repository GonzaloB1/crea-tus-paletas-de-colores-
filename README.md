# 🎨 Colorfly Studio

Aplicación web interactiva para **generar, copiar y guardar paletas de colores**.

Desarrollada con HTML, CSS y JavaScript Vanilla, con generación dinámica de colores, persistencia mediante `localStorage` y una interfaz responsive.

## 🌐 Demo

👉 [Ver Colorfly Studio](https://gonzalob1.github.io/crea-tus-paletas-de-colores-/)

## 📸 Vista previa

### Generación de paletas

![Paletas generadas](assets/paletas%20generadas.png)

### Selección de cantidad de colores

![Elegir cantidad](assets/elige%20cantidad.png)

### Copiar colores

![Copiar color](assets/copiar%20color.png)

### Paletas guardadas

![Paletas guardadas](assets/paletas%20guardadas.png)

## 🚀 Funcionalidades

- Generación aleatoria de paletas.
- Selección de **6, 8 o 9 colores**.
- Visualización en formatos **HEX y HSL**.
- Copiado de colores al portapapeles.
- Tooltips interactivos.
- Guardado de paletas favoritas.
- Persistencia mediante `localStorage`.
- Eliminación de paletas guardadas.
- Animaciones y transiciones.
- Diseño responsive.

## 🛠️ Tecnologías

- HTML5
- CSS3
- JavaScript Vanilla
- Flexbox
- Media Queries
- LocalStorage API
- Clipboard API

## 🧠 Decisiones técnicas

### Generación dinámica del DOM

Los colores se crean dinámicamente con JavaScript mediante elementos generados desde el DOM.

Esto permite cambiar fácilmente la cantidad de colores mostrados sin duplicar elementos en el HTML.

### Soporte HEX y HSL

La generación de colores está separada según el formato seleccionado, permitiendo trabajar con diferentes representaciones de color.

### Persistencia con localStorage

Las paletas favoritas se almacenan utilizando `localStorage`, por lo que permanecen disponibles después de cerrar o recargar la página.

### Interacción con el usuario

Se incorporaron tooltips, animaciones y feedback visual para hacer más intuitivas acciones como copiar un color o guardar una paleta.

## 📂 Estructura

```text
crea-tus-paletas-de-colores-/
├── assets/
├── index.html
├── style.css
├── script.js
└── README.md
```

## ⚙️ Ejecución local

### 1. Clonar el repositorio

```bash
git clone https://github.com/GonzaloB1/crea-tus-paletas-de-colores-.git
cd crea-tus-paletas-de-colores-
```

### 2. Abrir el proyecto

Podés abrir `index.html` directamente desde el navegador o utilizar **Live Server** desde Visual Studio Code.

No requiere instalación de dependencias.

## 🚀 Deploy

El proyecto está publicado mediante **GitHub Pages**.

Cada cambio realizado sobre la versión publicada puede desplegarse nuevamente desde la configuración de Pages del repositorio.

## 📚 Aprendizajes

Durante el desarrollo se trabajó principalmente con:

- Manipulación del DOM.
- Eventos en JavaScript.
- Generación dinámica de elementos.
- Manejo de estados en la interfaz.
- Persistencia con `localStorage`.
- Clipboard API.
- Diseño responsive.
- Flexbox.
- Animaciones CSS.
- Experiencia de usuario e interacciones visuales.

## 👨‍💻 Autor

**Gonzalo Bastias**

Frontend Developer Jr. | React · TypeScript · Node.js

- GitHub: [GonzaloB1](https://github.com/GonzaloB1)
- LinkedIn: [Gonzalo Bastias](https://www.linkedin.com/in/gonzalo-bastias-161320430/)

## 📄 Licencia

Copyright © 2026 Gonzalo Bastias — Colorfly Studio.

Proyecto desarrollado con fines educativos y de aprendizaje.