# Portafolio de Erick Agüero

Este es mi portafolio personal desarrollado con HTML, CSS y JavaScript vanilla.

## Características

- Diseño responsive y moderno
- Animaciones suaves y efectos visuales
- Sección de tecnologías y habilidades
- Proyectos destacados con slider
- Descarga de CV en PDF
- Efectos de partículas animadas

## Despliegue en Vercel

Para desplegar este portafolio en Vercel:

1. **Sube los archivos a tu repositorio de GitHub:**
   - `index.html` (copia de portfolio.html)
   - `portfolio.html`
   - `CV_ERICK_AGUERO.pdf`
   - `vercel.json`
   - `public/CV_ERICK_AGUERO.pdf`

2. **Conecta tu repositorio con Vercel:**
   - Ve a [vercel.com](https://vercel.com)
   - Importa tu repositorio de GitHub
   - Vercel detectará automáticamente la configuración

3. **Configuración automática:**
   - El archivo `vercel.json` configurará los headers correctos para archivos PDF
   - El archivo `index.html` servirá como página principal
   - Los archivos PDF estarán disponibles para descarga

## Estructura del proyecto

```
├── index.html              # Página principal (copia de portfolio.html)
├── portfolio.html          # Archivo principal del portafolio
├── CV_ERICK_AGUERO.pdf     # CV en PDF (en raíz)
├── vercel.json             # Configuración de Vercel
├── public/
│   └── CV_ERICK_AGUERO.pdf # CV en PDF (copia en public)
└── README.md               # Este archivo
```

## Solución de problemas

### Error de descarga de CV

Si el botón de descarga del CV no funciona:

1. **Verifica que el archivo PDF esté en la raíz del proyecto**
2. **Asegúrate de que el nombre del archivo coincida exactamente** (incluyendo mayúsculas/minúsculas)
3. **Verifica que el archivo esté también en la carpeta `public/`**

### Configuración de Vercel

El archivo `vercel.json` incluye:
- Headers correctos para archivos PDF
- Configuración de caché para mejor rendimiento

## Tecnologías utilizadas

- HTML5
- CSS3 (con variables CSS y animaciones)
- JavaScript (ES6+)
- Font Awesome (iconos)
- Vercel (hosting)

## Contacto

- GitHub: [@Erickaguero](https://github.com/Erickaguero)
- LinkedIn: [Erick Aguero](https://www.linkedin.com/in/erickagueroserrano/)
