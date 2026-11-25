# Portafolio 2026–2027 · Wael Boutafah Jebari

Repositorio base del portfolio profesional y académico de **Wael Boutafah Jebari**, estudiante de Desarrollo de Aplicaciones Web (DAW), con formación previa en Sistemas Microinformáticos y Redes (SMX).

> **Este repositorio contiene el código fuente y los recursos del portfolio. No tiene GitHub Pages configurado ni publica una web propia.** Para ver el resultado desplegado, utiliza los enlaces de Firebase o GitHub Pages indicados abajo.

## Portfolio desplegado

- **Firebase Hosting:** [portafolio-wael-jebari.web.app](https://portafolio-wael-jebari.web.app/)
- **GitHub Pages:** [waelbgg.github.io](https://waelbgg.github.io/)
- **Repositorio dedicado a GitHub Pages:** [Waelbgg/waelbgg.github.io](https://github.com/Waelbgg/waelbgg.github.io)

Los dos enlaces muestran la versión visual multipágina del portfolio. `Portafolio-26-27` sirve como repositorio base para conservar y actualizar su código y sus recursos; las publicaciones se administran por separado.

![Vista previa del portfolio de Wael Jebari](https://image.thum.io/get/width/1200/crop/800/noanimate/https://waelbgg.github.io/)

## Contenido

- **Inicio:** presentación, disponibilidad para prácticas y proyecto destacado.
- **Proyectos:** CV Responsive y proyectos personales/académicos.
- **DAW OS — Classroom Sync:** caso de estudio, ficha técnica, arquitectura, roadmap y demo.
- **Sobre mí:** trayectoria formativa, tecnologías y forma de trabajo.
- **Contacto y CV:** contacto, vista previa y descarga del currículum en PDF.
- **IA y automatización:** logos de ChatGPT, Claude y GitHub Copilot.

## DAW OS — Classroom Sync

DAW OS sincroniza tareas de Google Classroom con Notion mediante Google Apps Script. Nació cuando el calendario académico dejó de estar disponible: revisar cada curso manualmente era lento, desordenado y facilitaba olvidar entregas. La vista única de Notion también puede consultarse desde el móvil y se actualiza cada 15 minutos.

Una ejecución real revisó **8 cursos y 80 tareas**: 80 ya estaban sincronizadas, sin omisiones ni errores. Como no encontró cambios, ese ciclo comprobó consulta, comparación y detección de registros existentes, pero no ejercitó creación ni actualización. El código está en [Waelbgg/daw-os-classroom-sync](https://github.com/Waelbgg/daw-os-classroom-sync).

La demo del portfolio sigue siendo una simulación independiente con datos ficticios; no se conecta a las cuentas reales. La integración operativa conecta Classroom con Notion. La arquitectura puede ampliarse a otros servicios en el futuro.

## Estructura

```text
.
├── index.html                 # Inicio
├── proyectos/index.html       # Proyectos
├── daw-os/index.html          # Caso de estudio y demo de Classroom Sync
├── sobre-mi/index.html        # Trayectoria y tecnologías
├── contacto/index.html        # Contacto y CV
├── style.css                  # Estilos compartidos
├── portfolio-pages.css        # Estilos de las páginas interiores
├── portfolio.js               # Interacciones y navegación
├── enlaces-inicio.js          # Interacciones del inicio
├── daw-demo.js                # Simulación local con datos ficticios
├── cv-wael-jebari.pdf         # CV descargable
├── cv-wael-preview.png        # Vista previa del CV
├── cv-responsive.jpg          # Imagen del proyecto CV Responsive
├── logo-chatgpt.png           # Logo de ChatGPT
├── logo-claude.png            # Logo de Claude
├── logo-copilot.png           # Logo de GitHub Copilot
├── robots.txt                 # Directivas para crawlers
├── sitemap.xml                # Rutas públicas del sitio
└── .nojekyll                  # Marcador para publicación estática
```

## Desarrollo local

No requiere framework, instalación de paquetes ni proceso de compilación. Clona el repositorio y sirve la carpeta raíz con un servidor estático:

```bash
git clone https://github.com/Waelbgg/Portafolio-26-27.git
cd Portafolio-26-27
git switch main
python -m http.server 8000
```

Abre <http://localhost:8000>. También puede abrirse `index.html` directamente, aunque un servidor local representa mejor las rutas de las páginas internas.

## Tecnologías

HTML5 · CSS3 · JavaScript ES6+ · Git · GitHub · Firebase Hosting · GitHub Pages

El sitio utiliza HTML semántico, diseño responsive, recursos locales, navegación multipágina y JavaScript nativo. Incluye foco visible, enlace para saltar al contenido y respeto por la preferencia de movimiento reducido.

## Actualización y publicación

Este repositorio es la base del código. Los sitios de Firebase y GitHub Pages son despliegues visuales separados. Al cambiar el portfolio, comprueba las rutas internas y los recursos, actualiza los despliegues correspondientes y verifica sus URLs públicas. GitHub Pages **no está activado en este repositorio**.

Antes de publicar cambios, revisa:

- Que cada página cargue sus CSS, JavaScript, imágenes y PDF.
- La navegación interna en escritorio y móvil.
- Los filtros, la simulación, el registro y el reinicio de la demo ficticia de DAW OS.
- Los enlaces de correo y teléfono y la descarga del CV.
- Que la demo siga identificándose como simulación con datos ficticios, separada de la sincronización real.

## Contacto

- **GitHub:** [@Waelbgg](https://github.com/Waelbgg)
- **Correo:** [waelboutafah2007@gmail.com](mailto:waelboutafah2007@gmail.com)
- **Portfolio:** [GitHub Pages](https://waelbgg.github.io/) · [Firebase Hosting](https://portafolio-wael-jebari.web.app/)

---

_Portfolio personal y académico en desarrollo continuo · 2026–2027._
