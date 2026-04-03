# Portafolio Personal - Práctica Formativa Obligatoria 1

Este proyecto es un **Trabajo Práctico (TP)** correspondiente a la **Práctica Formativa Obligatoria 1 (PFO1)** de la materia de Desarrollo Frontend. Consiste en una Landing Page de portafolio personal construida exclusivamente con **HTML y CSS**, aplicando buenas prácticas de estructura semántica, diseño responsivo y accesibilidad web.

🔗 **URL de VERCEL:** 

---

## Checklist - Práctica Formativa Obligatoria 1

### Estructura del Proyecto:
- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] (Opcional) Carpeta `img` para recursos gráficos.
- [x] Archivo `README.md` creado, que incluya una breve descripción del TP y este checklist.

### Repositorio y Publicación:
- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando GitHub Pages.
- [x] En el `README.md` se indica la URL de GitHub Pages.

### Uso de Google Fonts:
- [x] Enlace a Google Fonts incluido en la sección `head` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] Redacta brevemente tu decisión: ¿Por qué elegiste esa fuente?

**Respuesta:** Elegí la fuente **Outfit** porque es una tipografía sans-serif moderna y geométrica que transmite profesionalismo y limpieza visual. Sus distintos pesos (300 a 700) permiten crear una jerarquía tipográfica clara entre títulos, subtítulos y texto de cuerpo, lo cual es ideal para un portafolio personal donde la legibilidad y la estética son fundamentales.

### HTML:
- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: charset y viewport.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

#### Secciones obligatorias en `main`:
- [x] Presentación Personal (`id="sobre-mi"`) con párrafo descriptivo e imagen con alt.
- [x] Tarjetas/Columnas (`id="tarjetas"`) con al menos 2 tarjetas con imagen y texto.
- [x] Listado de Habilidades (`id="habilidades"`) con tabla y listas organizadas.
- [x] Formulario de Contacto (`id="contacto"`) con campos Nombre, Apellido, Email, Teléfono y botón submit.
- [x] Películas Favoritas (`id="peliculas"`) con 3 películas, cada una con título, imagen y descripción.
- [x] Barra de navegación (`nav`) presente y contiene al menos 3 enlaces (tiene 5).
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

### CSS:
- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

#### Layout y Organización:
- [x] Se ha organizado el layout (especialmente en la sección "tarjetas") utilizando Flexbox o Grid.
- [x] Redacta: ¿Qué ventajas encontraste al utilizar Flexbox o Grid en tu proyecto?

**Respuesta:** Utilicé **CSS Grid** para la sección de tarjetas y habilidades, ya que permite crear layouts bidimensionales de forma sencilla y con `auto-fit` + `minmax()` se logra un diseño responsivo automático sin necesidad de muchos media queries. Para el héroe y las películas utilicé **Flexbox**, que es ideal para distribución unidimensional y alineación de elementos. La combinación de ambos me permitió crear un diseño complejo pero mantenible.

#### Estilización de Componentes:
- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `vh`).
- [x] Se ha implementado al menos una animación o transición (efecto hover en tarjetas, botones y películas).
- [x] Redacta: ¿Qué animación o transición implementaste y por qué consideraste que era adecuada para tu proyecto?

**Respuesta:** Implementé varias animaciones y transiciones: (1) **Hover en tarjetas de proyectos** con `translateY(-8px)` y `scale(1.08)` en la imagen para dar sensación de interactividad y profundidad. (2) **Glow pulsante** en la imagen de perfil usando `@keyframes pulse-glow` para agregar dinamismo visual al héroe. (3) **Hover en películas** con `translateX(8px)` para un efecto de deslizamiento sutil. (4) **Transiciones en el formulario** con cambio de borde y glow al hacer focus en los inputs. Estas animaciones son adecuadas porque mejoran la experiencia de usuario sin ser excesivas, guiando la atención del visitante.

### Consideraciones Adicionales:
- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos (mobile, tablet, desktop).
- [x] Se aplicaron buenas prácticas de accesibilidad (atributos `alt` en todas las imágenes, `label` en formularios, contraste de colores adecuado).
- [x] Se añadieron comentarios adicionales donde se describen decisiones de diseño y la lógica de implementación.
