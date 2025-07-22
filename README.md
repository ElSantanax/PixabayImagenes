# PixabayImagenes

Una aplicación web sencilla que permite buscar y visualizar imágenes utilizando la API de Pixabay. Incluye paginación y una interfaz responsiva con Tailwind CSS.

## Características
- Búsqueda de imágenes por término.
- Visualización de resultados con likes y vistas.
- Paginación dinámica.
- Enlace para ver la imagen en tamaño completo.
- Interfaz moderna usando Tailwind CSS.

## Instalación y uso
1. Clona este repositorio:
   ```bash
   git clone <url-del-repo>
   ```
2. Abre el archivo `index.html` en tu navegador web.

No se requiere instalación de dependencias adicionales, ya que todo el código es JavaScript puro y CSS.

## Estructura del proyecto
- `index.html`: Página principal de la aplicación.
- `js/app.js`: Lógica principal en JavaScript para búsqueda y paginación.
- `css/`: Estilos personalizados y Tailwind CSS.

## Personalización
Si deseas usar tu propia clave de API de Pixabay, reemplaza el valor de la variable `key` en `js/app.js`:
```js
const key = 'TU_API_KEY';
```
Puedes obtener una clave gratuita en [Pixabay API](https://pixabay.com/api/docs/).

## Créditos
- [Pixabay](https://pixabay.com/) por la API de imágenes.
- [Tailwind CSS](https://tailwindcss.com/) para los estilos.

## Licencia
Este proyecto está bajo la licencia MIT. 