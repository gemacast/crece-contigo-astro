# 🌱 Crece Contigo - Proyecto con Astro

Práctica del módulo de Desarrollo de Aplicaciones Web (DAW).

Este proyecto es una web sencilla orientada al crecimiento personal, desarrollada utilizando el framework Astro.

## ✅ Tecnologías utilizadas

- Astro – Framework moderno para sitios web rápidos
- HTML
- Bootstrap 5 – Framework CSS para diseño responsive
- Font Awesome – Iconos vectoriales
- React (futura integración)

## 📋 Requisitos previos
Antes de comenzar, tener instalado lo siguiente:

- Node.js (versión LTS recomendada)
- npm (viene con Node.js)
- Editor de código como Visual Studio Code
- Git (opcional, si usas control de versiones)


## 🔧 Instalación paso a paso

1. Instalar Node.js y npm
- Descargar desde: https://nodejs.org
- Instalar la versión LTS (recomendada)
- Verificar instalación:
```bash
node -v
npm -v
```

2. Crear el proyecto con Astro
```bash
npm create astro@latest
```

- Seleccionar la plantilla: Minimal
- Introducir el nombre o la ruta del proyecto: C:\xampp\htdocs\Practica_astro

## 📦 Dependencias e inicio del proyecto
### Instalar dependencias
```bash
npm install
```
4. Iniciar el servidor de desarrollo
```bash
npm run dev
```


- Abre en tu navegador: [http://localhost:4322](http://localhost:4322)  
  *(Si el puerto 4321 está ocupado, Astro usa otro como el 4322)*


## 🛠 Solución a problemas comunes

### Error: Ejecución de scripts deshabilitada en PowerShell

Si al ejecutar `npm` te aparece un error como este:

```plaintext
npm : No se puede cargar el archivo npm.ps1 porque la ejecución de scripts está deshabilitada.
```

Solución:

Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

## 📁 Estructura del proyecto

Practica_astro/
├── public/
├── src/
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── README.md

## 🌐 Estructura del sitio web

index.astro incluye:

 - Header: Logo y menú de navegación.
 - Banner principal: Título motivacional, subtítulo y botón de acción.
 - Temas destacados: Sección con tres columnas (Autoconocimiento, Hábitos y Bienestar, Metas y Productividad).
 - Frase inspiradora: Mensaje motivacional centrado.
 - Footer: Derechos de autor, contacto, redes sociales y enlaces legales.

## 📷 Recursos añadidos

Bootstrap CDN:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
```
Font Awesome CDN:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
```

## 🎨 Mejoras de estilo implementadas

- Degradado de fondo en el banner principal para profundidad visual.
- Imagen decorativa responsiva en el hero (lado derecho en escritorio, centrada en móvil).
- Botón destacado con color diferenciado (`btn-success`) y texto guía inferior.
- Cards con iconos ampliados (`fa-2xl`) y color (`text-primary`).
- Separadores visuales (`<hr>`) y márgenes uniformes (`my-4`, `py-5`, etc.).
- Accesibilidad: uso de `aria-label` en botones repetidos.
- Semántica: inclusión de etiquetas `<article>` para los pilares.
- Icono decorativo (`fa-quote-left`) en la sección de frase motivadora.

## 📷 Recursos añadidos

**Bootstrap CDN:**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
'''


🔗 **Web publicada:**  
https://crece-contigo-astro.vercel.app

Web sencilla orientada al crecimiento personal, desarrollada utilizando el framework Astro.

## 🎯 Objetivos del proyecto

- Practicar estructura HTML semántica.
- Utilizar Bootstrap para un diseño responsive y moderno.
- Preparar el proyecto para futura integración de React.
- Crear una web modular, clara y orientada al usuario.
- Aplicar buenas prácticas de desarrollo web.

## 👩‍💻 Autor/a

- Nombre: Gemma Castells
- Módulo: Desarrollo de Aplicaciones Web (DAW)
- Fecha: Abril 2025