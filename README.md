# Joshua Portafolio

Primer portafolio de desarrollo web de **Joshua Lozada**, estudiante de Medios Interactivos en la Universidad San Francisco de Quito (USFQ). El sitio es estático: HTML, CSS y JavaScript en cada página, listo para abrir, sin gestor de paquetes ni compilador.

Presenta su perfil, una galería de seis trabajos (programación, fotografía y animación) y un formulario de contacto.

**Sitio en línea:** [https://scorpwik.github.io/portafolio-web-v1/](https://scorpwik.github.io/portafolio-web-v1/)

La pestaña de inicio se titula «Joshua Portafolio». El encabezado dice «SOY JOSHUA, DISEÑADOR WEB».

## Secciones

El menú (≡) está en todas las páginas y enlaza estas cuatro:

| Sección | Archivo | Contenido |
| --- | --- | --- |
| Inicio | `index.html` | Presentación, foto, GitHub, LinkedIn y un resumen de perfil y de proyectos. |
| Proyectos | `paginas/projects.html` | Galería de seis fichas, en dos páginas. |
| Acerca de mí | `paginas/about_me.html` | Trayectoria y habilidades técnicas. |
| Contáctame | `paginas/contacto.html` | Formulario que abre el correo de Joshua. |

En la barra del inicio también está el acceso directo a Contacto. La flecha bajo el encabezado lleva a la galería.

### Inicio

- Foto en `assets/yo.png`.
- Enlaces a [GitHub](https://github.com/Scorpwik) y a [LinkedIn](https://www.linkedin.com/in/joshua-lozada-95817a232).
- El texto de perfil lo presenta como estudiante de Medios Interactivos en la USFQ, con interés en el desarrollo de software, las experiencias digitales y Processing.
- El bloque de proyectos habla de aplicaciones interactivas, videojuegos experimentales y scripts de automatización visual. Las fichas publicadas son las seis de la galería.

### Acerca de mí

La página resume su enfoque: programación aplicada al diseño, Processing para sistemas visuales, postproducción digital e interfaces.

Las habilidades aparecen con estos títulos:

- **Creative & Post-Production:** fotografía (captura, composición e iluminación), Photoshop, Lightroom, Premiere Pro, After Effects e Illustrator.
- **Programming & Development:** Processing para arte generativo e interactividad, Java, C++ y Visual Basic.

Esas herramientas están descritas en la página. El código de este repositorio es el sitio que las muestra.

### Proyectos

La galería tiene dos páginas, con los botones 1 y 2. Al regresar desde los proyectos 4, 5 y 6, el enlace vuelve a `projects.html?page=2`.

1. **Videojuego experimental** (`paginas/project1.html`). Programación, 2026. Juego espacial hecho en Processing y Java. El video está en `assets/gameplay1.mp4`. El botón «Ver repositorio en GitHub» abre el perfil [Scorpwik](https://github.com/Scorpwik).
2. **Bypass** (`paginas/project2.html`). Fotografía, 2025. Serie sobre la introspección y la dualidad entre la imagen pública y el mundo interior. Carrusel de nueve fotos (`assets/foto1.jpg` a `foto9.jpg`) con vista ampliada. Postproducción en Photoshop y Lightroom. Toma con Canon EOS 90D, lentes 18-55 mm y 18-135 mm.
3. **Imponencia natural** (`paginas/project3.html`). Fotografía, 2024. Aves para un certamen ecuatoriano de naturaleza. Carrusel de ocho fotos (`assets/ave1.jpg` a `ave8.jpg`) con vista ampliada. Misma postproducción y el mismo equipo que Bypass.
4. **Conservación Galápagos** (`paginas/project4.html`). Animación, 2025. Tres clips educativos incrustados desde YouTube, hechos con After Effects e Illustrator, para una campaña de conservación dirigida a niños de escuelas locales.
5. **Videoclip 3D** (`paginas/project5.html`). Animación, 2025. Viaje espacial con cámaras virtuales y paralaje en After Effects, e ilustración en Illustrator. El video está en `assets/v1.mp4`.
6. **Compost orgánico** (`paginas/project6.html`). Animación, 2026. Pieza educativa en formato vertical 9:16 sobre compost con café y plátano. After Effects e Illustrator. El video está en `assets/v2.mp4`.

### Contacto

El formulario pide nombre, teléfono, sexo y una breve descripción. Cada campo se vacía con el botón X. Al enviar, el navegador abre un correo a `joshua-lozada@hotmail.com` mediante `mailto:`. Lo recibe el programa de correo de la computadora.

El pie de cada página dice «© 2026 Joshua Lozada | Medios Interactivos».

## Tecnologías

Lo que usa este repositorio:

- HTML5, con `lang="es"`.
- CSS3 en un solo archivo, `estilos/web.css`. Las fuentes son Arial, Helvetica y Courier New, las del sistema.
- JavaScript escrito en cada página: menú, cambio de página en la galería, carruseles, vista ampliada de las fotos y el cambio entre los tres clips de YouTube.
- Imágenes JPG y PNG, y videos MP4.
- GitHub Pages, con la rama `main` publicada desde la carpeta raíz.

## Cómo verlo en tu computadora

1. Clona el repositorio y entra a la carpeta:

   ```bash
   git clone https://github.com/Scorpwik/portafolio-web-v1.git
   cd portafolio-web-v1
   ```

2. Sirve los archivos y abre [http://localhost:8000](http://localhost:8000):

   ```bash
   python3 -m http.server 8000
   ```

También puedes abrir `index.html` directo en el navegador. Las páginas, el CSS y las imágenes usan rutas relativas. Para reproducir los MP4 conviene el servidor local: varios navegadores limitan el video cuando el archivo se abre desde el disco.

## Publicación

Repositorio: [Scorpwik/portafolio-web-v1](https://github.com/Scorpwik/portafolio-web-v1).

GitHub Pages sirve la rama `main` desde `/`. La dirección vigente es [https://scorpwik.github.io/portafolio-web-v1/](https://scorpwik.github.io/portafolio-web-v1/).

Los estilos, las páginas y las imágenes se enlazan con rutas relativas al archivo (`estilos/web.css`, `paginas/projects.html`, `../assets/p1.jpg`). GitHub Pages las resuelve dentro de `portafolio-web-v1`.

## Estructura

```text
index.html
estilos/web.css
paginas/
  about_me.html
  contacto.html
  projects.html
  project1.html
  project2.html
  project3.html
  project4.html
  project5.html
  project6.html
assets/
  fotos, retrato y videos del sitio
```

## Autor

**Joshua Lozada**  
Estudiante de Medios Interactivos, USFQ

- GitHub: [https://github.com/Scorpwik](https://github.com/Scorpwik)
- LinkedIn: [https://www.linkedin.com/in/joshua-lozada-95817a232](https://www.linkedin.com/in/joshua-lozada-95817a232)
- Correo: [joshua-lozada@hotmail.com](mailto:joshua-lozada@hotmail.com)
