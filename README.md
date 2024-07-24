## Porfolio Agustín Rodríguez - Astro

## 🚀 Estructura del Proyecto

Dentro del proyecto Astro, encontrarás la siguiente estructura de carpetas y archivos:

/
├── public/
│ ├── assets
│ │ ├── fonts
│ │ └── images
│ └── favicon.ico
├── src/
│ ├── components/
│ │ ├── home/
│ │ └── general/
│ │ ├── Header.astro
│ │ ├── Footer.astro
│ │ └── ...
│ ├── data/
│ ├── layouts/
│ │ ├── Layout.astro
│ │ └── ...
│ ├── pages/
│ │ ├── projects.astro
│ │ ├── index.astro
│ ├── styles/
│ │ ├── custom-styles.css
│ │ ├── fonts.css
│ │ └── styles.css
│ ├── types/
│ ├── utils/
├── package.json
└── ...

- **`src/pages/`**: Astro busca archivos `.astro` o `.md` en este directorio. Cada archivo se convierte en una ruta basada en su nombre de archivo.
- **`src/components/`**: Aquí es donde puedes colocar cualquier componente Astro/React/Vue/Svelte/Preact.
- **`public/assets/`**: Coloca aquí tus activos estáticos, como imágenes.
- **`src/data/`**: Guarda aquí tus datos personales y otra información relevante.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                | Acción                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Instala las dependencias                        |
| `npm run dev`          | Inicia el servidor de desarrollo local en `localhost:3000` |
| `npm run build`        | Construye tu sitio para producción en `./dist/` |
| `npm run preview`      | Previsualiza tu construcción localmente, antes de desplegar |
| `npm run astro ...`    | Ejecuta comandos CLI como `astro add`, `astro check` |
| `npm run astro --help` | Obtén ayuda usando el CLI de Astro               |

## 👀 ¿Quieres aprender más?

Consulta la [documentación de Astro](https://docs.astro.build) o únete al [servidor de Discord de Astro](https://astro.build/chat) para obtener más información y soporte.
