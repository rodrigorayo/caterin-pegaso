# Guía de Herramientas: Astro y Tailwind CSS

Esta guía es para ayudarte a entender y trabajar con las herramientas que hemos configurado para tu Landing Page de catering saludable.

## 🚀 Astro
**Astro** es un framework web diseñado para ser extremadamente rápido. A diferencia de otros frameworks que envían mucho código a tu navegador, Astro envía "cero JavaScript" por defecto, lo que hace que tu página cargue instantáneamente.

### ¿Cómo usar Astro localmente?
1. **Instalar dependencias**: Si acabas de descargar el proyecto, abre una terminal en la carpeta del proyecto y ejecuta:
   ```bash
   npm install
   ```
2. **Iniciar el servidor de desarrollo**:
   ```bash
   npm run dev
   ```
   Esto te dará una URL (usualmente `http://localhost:4321`) que puedes abrir en tu navegador. Los cambios que hagas en el código se actualizarán en vivo.
3. **Construir para producción**:
   ```bash
   npm run build
   ```
   Este comando genera los archivos finales optimizados listos para subir a cualquier hosting (Vercel, Netlify, tu propio servidor).

---

## 🎨 Tailwind CSS
**Tailwind CSS** es un framework de diseño "utility-first". En lugar de escribir archivos CSS separados con nombres de clases abstractos, usas clases predefinidas directamente en tu HTML.

### Ejemplos Básicos:
- `text-green-600`: Cambia el color del texto a verde.
- `bg-white`: Cambia el fondo a blanco.
- `p-4`: Agrega "padding" (espacio interior) de tamaño 4.
- `rounded-lg`: Redondea los bordes del elemento de forma "large".
- `hover:bg-green-700`: Cambia el fondo a un verde más oscuro cuando pasas el mouse por encima.

En este proyecto, hemos configurado los colores principales para enfocarnos en los tonos **Verde** y **Blanco**, ideales para transmitir la idea de comida fresca y saludable.

### ¿Dónde encuentro el código principal?
- **`src/pages/index.astro`**: Aquí está el código de tu Landing Page principal. Puedes editar los textos directamente en este archivo.
- **`src/components/`**: (Si existen) Aquí guardamos partes de la página que se pueden reutilizar, como botones o tarjetas de menú.

¡Eso es todo! Con `npm run dev` puedes empezar a ver los cambios en vivo y con las clases de Tailwind es muy fácil cambiar colores, tamaños y márgenes.
