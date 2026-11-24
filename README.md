# Pagina-web — Victorius y la Ciencia (Créditos del Equipo)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

Página web estática desarrollada con HTML y CSS por **Ricardo Rojas** (estudiante de **Ingeniería en Sistemas Computacionales**), creada originalmente para la sección **"Créditos del Equipo"** de *Victorius y la Ciencia*, un proyecto escolar de revista científica de la **Escuela Secundaria Oficial No. 0940 Octavio Paz**.

Este repositorio forma parte de mis primeros proyectos en desarrollo web y está enfocado en presentar los créditos del equipo con una animación continua tipo cierre de película.

## Tecnologías utilizadas

- **HTML5**: Estructura semántica para los créditos de los colaboradores y el mensaje de cierre.
- **CSS3**: Maquetación con Flexbox, estilo circular para avatares, animación continua con `@keyframes scroll` y `media queries` responsivas.

## Características principales

- **Créditos con desplazamiento animado**: Animación vertical continua (`60s linear infinite`) sobre un diseño oscuro inspirado en créditos cinematográficos.
- **Créditos por sección**: Muestra el nombre de cada integrante, la sección de la revista en la que participó y su espacio para fotografía circular.
- **Diseño adaptable**: Cambia automáticamente de una vista apilada en dispositivos móviles a tarjetas horizontales a partir de `min-width: 600px`.

## Estructura del proyecto

```text
Pagina-web/
├── PaginaWeb.HTML
└── README.md
```

## Cómo probarlo en tu computadora

1. Clona el repositorio en tu equipo:
   ```bash
   git clone https://github.com/ReySombras12/Pagina-web.git
   ```
2. Abre el archivo `PaginaWeb.HTML` directamente en cualquier navegador web moderno.

> **Nota:** Las imágenes de perfil (`imagen1.jpg`–`imagen5.jpg`) referenciadas en el HTML se encuentran almacenadas en el repositorio complementario [`ReySombras12.github.io`](https://github.com/ReySombras12/ReySombras12.github.io).

## Aprendizajes y retos

Este trabajo representó uno de mis primeros acercamientos prácticos a HTML y CSS. Me ayudó a comprender cómo usar Flexbox para organizar tarjetas, trabajar con animaciones CSS puras (`@keyframes`) sin JavaScript y adaptar el diseño para que se vea ordenado tanto en celular como en computadora.
