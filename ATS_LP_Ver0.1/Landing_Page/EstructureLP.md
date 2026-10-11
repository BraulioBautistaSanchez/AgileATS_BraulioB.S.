# Justificación de la estructura

## 1. ¿Por qué una landing page de una sola página?

- El proyecto está en **etapa temprana de producción**: aún no hay suficiente contenido para un sitio multipágina.
- Una landing concentra la atención del visitante en **un solo objetivo** (pre-registrarse) sin distracciones.
- Es más fácil de mantener, rápida de cargar y adecuada para móviles.
- La navegación por anclas (`#historia`, `#caracters`, etc.) permite recorrer todo con un clic.

## 2. Flujo narrativo de las secciones

La estructura sigue un recorrido pensado como **embudo de interés**: de lo general a lo específico, y de lo emocional a la acción.

```
Hero → Historia → Personajes → Noticias → Black Studios → Footer
```

| Sección | Propósito | Justificación |
|---|---|---|
| **Header / Nav** | Orientar al usuario | Acceso rápido a cualquier parte; `aria-label` mejora la accesibilidad. |
| **Hero (`#hero`)** | Captar atención y convertir | Es lo primero que se ve: título, subtítulo, sinopsis corta y botón *Pre-Registrarse ya*. Responde en segundos "¿qué es esto?". |
| **Historia (`#history`)** | Contextualizar y generar curiosidad | Explica el trasfondo (2006, operación encubierta, reapertura del caso) sin spoilers. Prepara emocionalmente al usuario. |
| **Personajes (`#caracters`)** | Crear conexión emocional | En una aventura narrativa, los personajes son el principal atractivo. |
| **Noticias (`#news`)** | Mostrar que el proyecto está vivo | Informa sobre el avance (producción, DEMO) y fomenta que el usuario regrese. |
| **Black Studios (`#studio`)** | Dar identidad y abrir comunicación | Presenta al estudio (pendiente a  ofrecer formulario de contacto para colaboraciones, prensa, escuelas o feedback.) |
| **Footer** | Cierre legal e institucional | Derechos de autor y datos básicos. |

## 3. Decisiones técnicas y de semántica

- **HTML5 semántico** (`header`, `nav`, `main`, `section`, `footer`): mejora SEO, accesibilidad y mantenimiento.
- **`aria-labelledby` en cada sección:** los lectores de pantalla identifican cada bloque por su título.
- **`<meta name="description">` y `<title>`:** necesarios para posicionamiento en buscadores y vista previa al compartir.
- **`<meta name="viewport">`:** base del diseño responsive.
- **`lang="es"`:** indica el idioma principal al navegador y a los buscadores.
- **Formulario con `label` + `for`, `required` y tipo `email`:** accesible y con validación nativa.
- **Un solo `<h1>`:** jerarquía de encabezados clara (h1 → h2).
- **Botón CTA (`.btn-cta`) en el hero:** acción principal visible sin necesidad de hacer scroll.

## 4. Justificación desde los usuarios

| Perfil | Qué necesita | Sección que lo atiende |
|---|---|---|
| Jugadores interesados | Detalles del juego y pre-registro | Hero, Historia, Personajes |
| Jugadores casuales | Entender rápido de qué va | Hero |
| Estudiantes y compañeros | Ver el proyecto y el equipo | Black Studios, Noticias |
| Maestros | Evaluar estructura y calidad | Toda la página, semántica y accesibilidad |
| Público objetivo | Interés por la temática histórica | Historia, Personajes |

