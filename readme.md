# DEV-09 Modern Portfolio Template: ¡Lanza tu Portafolio de Desarrollador con Estilo!

[![Ver Demo en Vivo](https://img.shields.io/badge/Ver%20Demo-En%20Vivo-brightgreen?style=for-the-badge&logo=netlify)](ENLACE_A_TU_DEMO_AQUI) **DEV-09** es un template de portafolio para desarrolladores moderno, elegante y completamente responsivo, construido con **HTML5, CSS3 y Tailwind CSS**. Diseñado para ser fácilmente personalizable, es perfecto tanto para desarrolladores que están comenzando y quieren una presencia online profesional rápidamente, como para desarrolladores experimentados que buscan actualizar su portafolio con un diseño actual.

[Imagen de Portada del Template - Ejemplo: Captura de pantalla del Hero Section]

## ✨ Características Destacadas

* 🎨 **Diseño Moderno y Limpio:** Causa una primera impresión impactante.
* 📱 **Totalmente Responsivo:** Se ve increíble en cualquier dispositivo, desde móviles hasta pantallas de escritorio.
* 🚀 **Optimizado para la Velocidad:** Código ligero para tiempos de carga rápidos.
* 🖌️ **Fácilmente Personalizable con Tailwind CSS:**
    * Cambia el color de acento principal en un solo lugar (`style.css`).
    * Utiliza las clases de utilidad de Tailwind para modificar cualquier aspecto.
* 📜 **Scroll Suave y Animaciones Sutiles:** Efectos de aparición (`animate-on-scroll`) para una experiencia de usuario dinámica y agradable.
* 🧩 **Secciones Predefinidas y Bien Estructuradas:**
    * Hero (Inicio con tu nombre y título)
    * About (Sobre mí, historia, habilidades con barras de progreso)
    * Services (Qué ofreces)
    * Tech Stack (Iconos de tecnologías que dominas)
    * Portfolio (Muestra tus proyectos)
    * Testimonial (Opcional, para mostrar feedback de clientes)
    * Blog (Pequeña sección para tus últimos artículos)
    * Contact (Formulario de contacto funcional - requiere configuración de backend o servicio externo)
* 📝 **Comentado para Fácil Entendimiento:** Código organizado y con comentarios donde es necesario.
* 🌐 **Listo para Desplegar:** Sube los archivos a tu hosting preferido y ¡listo!
* 🔗 **Iconos Incluidos:** Usa Devicon para los iconos de tecnología y Heroicons para iconos de UI.

## 🛠️ Stack Tecnológico

* **HTML5** (Semántico y bien estructurado)
* **CSS3** (Estilos personalizados y animaciones)
* **Tailwind CSS v3** (Framework CSS utility-first para desarrollo rápido)
* **JavaScript Vanilla** (Para interacciones como el menú móvil, scroll suave y animaciones al hacer scroll)

## 🚀 Cómo Empezar

1.  **Descarga el Template:**
    * Obtén el archivo `.zip` después de tu compra o descarga.
    * Descomprímelo en tu máquina local.

2.  **Abre `index.html` en tu Navegador:**
    * Para ver el template localmente, simplemente abre el archivo `index.html` en tu navegador web preferido.

3.  **Personalización:**
    * **Textos:** Edita directamente el contenido en el archivo `index.html`. Busca los textos de ejemplo y reemplázalos con tu información personal (nombre, descripción, detalles de proyectos, etc.).
    * **Imágenes:**
        * Las imágenes de ejemplo se encuentran en la carpeta `assets/img/`.
        * Reemplaza las imágenes `1.png` a `9.png` (y `testimonialImage.png` si es diferente) con tus propias imágenes. Intenta mantener dimensiones similares para un mejor ajuste o ajusta el CSS si es necesario.
        * **IDs de Imágenes:** Las imágenes principales tienen IDs como `heroImage`, `experienceImage`, `project1Image`, etc., para facilitar su identificación.
    * **Color de Acento:**
        * El color de acento principal (actualmente rojo) se define en `assets/styles/style.css`.
        * Busca la variable `--accent-color` y cambia su valor hexadecimal (ej. `#DC2626`) al color que prefieras.
        * También actualiza `--accent-color-rgb` con los valores RGB correspondientes a tu nuevo color de acento para que las sombras que lo usan funcionen correctamente.
        ```css
        /* assets/styles/style.css */
        body {
            /* ... otros estilos ... */
            --accent-color: #SU_NUEVO_COLOR_HEX; /* Ej: #3B82F6 para azul Tailwind blue-500 */
            --accent-color-rgb: SU_NUEVO_COLOR_R, SU_NUEVO_COLOR_G, SU_NUEVO_COLOR_B; /* Ej: 59, 130, 246 */
        }
        ```
    * **Enlaces Sociales y de Navegación:** Actualiza los `href` en la sección `<nav>` y en el pie de página o sección de contacto según necesites.
    * **Formulario de Contacto:** El formulario en `index.html` es solo la estructura HTML. Para hacerlo funcional, necesitarás integrarlo con un servicio de backend (como Formspree, Netlify Forms, Getform) o tu propio script de servidor.
    * **Contenido de Secciones:**
        * **Tech Stack:** Los iconos provienen de Devicon. Puedes encontrar más iconos en [Devicon Website](https://devicon.dev/) y añadir/modificar las clases `devicon-*` en la sección `tech-stack`.
        * **Proyectos:** Actualiza las imágenes, títulos, descripciones y enlaces de tus proyectos.

4.  **Despliegue:**
    * Una vez que estés contento con tu personalización, puedes desplegar tu portafolio en cualquier servicio de hosting estático. Algunas opciones populares y gratuitas son:
        * [GitHub Pages](https://pages.github.com/)
        * [Netlify](https://www.netlify.com/)
        * [Vercel](https://vercel.com/)
    * Simplemente sube la carpeta completa del proyecto a la plataforma elegida.

## 📁 Estructura de Archivos


dev-09-portfolio-template/
├── assets/
│   ├── img/          # Imágenes del template (reemplazar con las tuyas)
│   │   ├── 1.png
│   │   ├── ...
│   │   └── 9.png
│   └── styles/
│       └── style.css # Estilos CSS personalizados y definición del color de acento
├── index.html        # El archivo principal de tu portafolio
└── readme.md         # Este archivo


## 📄 Licencia

**Licencia de Uso (Tras la Compra):**

Al adquirir este template, obtienes el derecho a:

* **Utilizar el template para un (1) proyecto final.** Este proyecto puede ser para uso personal o para un cliente.
* **Modificar el template** según las necesidades de dicho proyecto final. Puedes cambiar colores, fuentes, contenido, estructura y añadir o quitar secciones.

Restricciones:

* **No puedes revender, redistribuir o volver a licenciar el template original o modificado**, ni ninguna de sus partes, ya sea de forma gratuita o con fines de lucro.
* **No puedes utilizar el template (o partes de él) para crear otro template, tema, kit de UI o cualquier producto digital destinado a la venta o distribución.**
* La licencia es **no transferible**. Solo el comprador original tiene derecho a usar el template según estos términos.

Si deseas utilizar el template en **múltiples proyectos**, por favor, adquiere una licencia adicional por cada proyecto o contacta a **Jeshersin_09** para discutir opciones de licenciamiento extendido.

## 💬 Soporte y Contacto

Si tienes preguntas sobre la personalización básica o encuentras algún problema con el template, puedes contactar a **Jeshersin_09** en jeshermendieta@gmail.com.

## 🙏 Créditos y Agradecimientos

* Iconos de tecnología por [Devicon](https://devicon.dev/).
* Algunos iconos de UI inspirados o tomados de [Heroicons](https://heroicons.com/).
* Imágenes de placeholder de [Unsplash](https://unsplash.com/) o generadas (reemplazar con las tuyas).
* Fuente "Inter" de [Google Fonts](https://fonts.google.com/specimen/Inter).

---

© DEV-09 (Un producto de Jesher Mednieta - Jeshersin_09). Todos los derechos reservados.
