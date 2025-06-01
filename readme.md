# DEV-09 Modern Portfolio Template

**[English](#english) | [Español](#español)**

---
<a name="english"></a>

## DEV-09 Modern Portfolio Template: Launch Your Developer Portfolio in Style! (English)

[![View Live Demo](https://img.shields.io/badge/View%20Demo-Live-brightgreen?style=for-the-badge&logo=netlify)](YOUR_DEMO_LINK_HERE) **DEV-09** is a modern, elegant, and fully responsive developer portfolio template, built with **HTML5, CSS3, and Tailwind CSS**. Designed for easy customization, it's perfect for both developers who are just starting and want a professional online presence quickly, as well as experienced developers looking to update their portfolio with a current design.

[Cover Image of the Template - Example: Screenshot of the Hero Section]

## ✨ Key Features

* 🎨 **Modern and Clean Design:** Make a striking first impression.
* 📱 **Fully Responsive:** Looks amazing on any device, from mobile phones to desktop screens.
* 🚀 **Optimized for Speed:** Lightweight code for fast loading times.
* 🖌️ **Easily Customizable with Tailwind CSS:**
    * Change the main accent color in one place (`style.css`).
    * Use Tailwind utility classes to modify any aspect.
* 📜 **Smooth Scroll and Subtle Animations:** On-scroll reveal effects (`animate-on-scroll`) for a dynamic and pleasant user experience.
* 🧩 **Predefined and Well-Structured Sections:**
    * Hero (Homepage with your name and title)
    * About (About me, story, skills with progress bars)
    * Services (What you offer)
    * Tech Stack (Icons of technologies you master)
    * Portfolio (Showcase your projects)
    * Testimonial (Optional, to display client feedback)
    * Blog (Small section for your latest articles)
    * Contact (Functional contact form - requires backend setup or external service)
* 📝 **Commented for Easy Understanding:** Organized code with comments where necessary.
* 🌐 **Ready to Deploy:** Upload the files to your preferred hosting and you're set!
* 🔗 **Icons Included:** Uses Devicon for technology icons and Heroicons for UI icons.

## 🛠️ Tech Stack

* **HTML5** (Semantic and well-structured)
* **CSS3** (Custom styles and animations)
* **Tailwind CSS v3** (Utility-first CSS framework for rapid development)
* **Vanilla JavaScript** (For interactions like the mobile menu, smooth scroll, and scroll animations)

## 🚀 Getting Started

1.  **Download the Template:**
    * Get the `.zip` file after your purchase or download.
    * Unzip it on your local machine.

2.  **Open `index.html` in Your Browser:**
    * To view the template locally, simply open the `index.html` file in your preferred web browser.

3.  **Customization:**
    * **Texts:** Directly edit the content in the `index.html` file. Look for the example texts and replace them with your personal information (name, description, project details, etc.).
    * **Images:**
        * Example images are located in the `assets/img/` folder.
        * Replace images `1.png` to `9.png` (and `testimonialImage.png` if different) with your own images. Try to maintain similar dimensions for a better fit or adjust the CSS if necessary.
        * **Image IDs:** Main images have IDs like `heroImage`, `experienceImage`, `project1Image`, etc., for easy identification.
    * **Accent Color:**
        * The main accent color (currently red) is defined in `assets/styles/style.css`.
        * Look for the `--accent-color` variable and change its hexadecimal value (e.g., `#DC2626`) to your preferred color.
        * Also, update `--accent-color-rgb` with the corresponding RGB values for your new accent color so that shadows using it work correctly.
        ```css
        /* assets/styles/style.css */
        body {
            /* ... other styles ... */
            --accent-color: #YOUR_NEW_HEX_COLOR; /* Ex: #3B82F6 for Tailwind blue-500 */
            --accent-color-rgb: YOUR_NEW_R_COLOR, YOUR_NEW_G_COLOR, YOUR_NEW_B_COLOR; /* Ex: 59, 130, 246 */
        }
        ```
    * **Social and Navigation Links:** Update the `href` attributes in the `<nav>` section and in the footer or contact section as needed.
    * **Contact Form:** The form in `index.html` is just the HTML structure. To make it functional, you'll need to integrate it with a backend service (like Formspree, Netlify Forms, Getform) or your own server-side script.
    * **Section Content:**
        * **Tech Stack:** Icons are from Devicon. You can find more icons on the [Devicon Website](https://devicon.dev/) and add/modify the `devicon-*` classes in the `tech-stack` section.
        * **Projects:** Update the images, titles, descriptions, and links for your projects.

4.  **Deployment:**
    * Once you're happy with your customization, you can deploy your portfolio on any static hosting service. Some popular and free options are:
        * [GitHub Pages](https://pages.github.com/)
        * [Netlify](https://www.netlify.com/)
        * [Vercel](https://vercel.com/)
    * Simply upload the entire project folder to your chosen platform.

## 📁 File Structure


dev-09-portfolio-template/
├── assets/
│   ├── img/          # Template images (replace with yours)
│   │   ├── 1.png
│   │   ├── ...
│   │   └── 9.png
│   └── styles/
│       └── style.css # Custom CSS styles and accent color definition
├── index.html        # The main file for your portfolio
└── readme.md         # This file


## 📄 License

**Usage License (Upon Purchase):**

By purchasing this template, you are granted the right to:

* **Use the template for one (1) final project.** This project can be for personal use or for a client.
* **Modify the template** according to the needs of said final project. You can change colors, fonts, content, structure, and add or remove sections.

Restrictions:

* **You may not resell, redistribute, or re-license the original or modified template**, or any of its parts, whether for free or for profit.
* **You may not use the template (or parts of it) to create another template, theme, UI kit, or any digital product intended for sale or distribution.**
* The license is **non-transferable**. Only the original purchaser has the right to use the template according to these terms.

If you wish to use the template on **multiple projects**, please purchase an additional license for each project or contact **Jeshersin_09** to discuss extended licensing options.

## 💬 Support and Contact

If you have questions about basic customization or encounter any issues with the template, you can contact **Jeshersin_09** at jeshermendieta@gmail.com.

## 🙏 Credits and Acknowledgements

* Technology icons by [Devicon](https://devicon.dev/).
* Some UI icons inspired by or taken from [Heroicons](https://heroicons.com/).
* Placeholder images from [Unsplash](https://unsplash.com/) or generated (replace with yours).
* "Inter" font from [Google Fonts](https://fonts.google.com/specimen/Inter).

---

© DEV-09 (A product of Jesher Mednieta - Jeshersin_09). All rights reserved.

---
<a name="español"></a>

## DEV-09 Modern Portfolio Template: ¡Lanza tu Portafolio de Desarrollador con Estilo! (Español)

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
