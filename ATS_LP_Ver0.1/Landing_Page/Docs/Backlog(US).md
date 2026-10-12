# Product Backlog – User Stories

**Proyecto:** After The Storm (ATS) – Landing page
**Formato:** *Como [usuario], quiero [acción], para [beneficio].*
**Priorización:**  (Alta / media / baja / NA)

---

## Épicas

| ID | Épica | Descripción |
|---|---|---|
| E1 | Presentación del juego | Comunicar qué es ATS y convertir |
| E2 | Narrativa y personajes | Contar la historia y presentar el elenco |
| E3 | Navegación y experiencia | Usabilidad, accesibilidad y responsive |
| E4 | Estudio y contacto | Identidad de Black Studios y comunicación |
| E5 | Noticias | Mantener informados a los usuarios |


---

## Backlog resumido

| ID | Épica | User Story (resumen) | Prioridad | Sprint |
|---|---|---|---|---|
| US-01 | E1 | Ver título y sinopsis en el hero | Alta | 1 |
| US-02 | E1 | Botón *Pre-Regristro ya* visible | Alta | 1 |
| US-03 | E3 | Menú de navegación | Alta | 2 |
| US-04 | E2 | Leer la historia del juego | Alta | 2 |
| US-05 | E2 | Conocer a los personajes | Alta | 3 |
| US-06 | E4 | Conocer a Black Studios | media | 3 |
| US-07 | E3 | Ver la página correctamente en móvil | Alta | 4 |
| US-08 | E3 | Navegación accesible (teclado y lector de pantalla) | media | 4 ||
| US-09 | E3 | Menú que se mantenga visible al hacer scroll | baja | 5 |
| US-10 | E5 | Leer las noticias del desarrollo | baja | 5 |

---

## Detalle de historias

### US-01 · Hero con título y sinopsis
Como visitante, quiero ver el nombre del juego y una breve sinopsis al entrar, para entender de qué trata en pocos segundos.
**Criterios de aceptación**
- Se muestran `h1` (ATS) y subtítulo (After The Storm).
- La sinopsis tiene máximo 3 líneas en escritorio.
- Todo es visible sin hacer scroll.

### US-02 · Botón de pre-registro
Como jugador interesado, quiero un botón claro de *Pre-registro ya*, para apartar el juego fácilmente.
**Criterios de aceptación**
- El botón destaca visualmente (contraste y tamaño).
- Redirige a la página de pre-registro (o `#` mientras no exista).
- Tiene estado *hover* y *focus*.

### US-03 · Menú de navegación
Como visitante, quiero un menú con enlaces a cada sección, para moverme rápidamente por la página.
**Criterios de aceptación**
- Enlaces: Inicio, Historia, Personajes, Noticias, Black Studios.
- Cada enlace lleva a su sección con desplazamiento suave.
- Funciona con teclado (Tab/Enter).

### US-04 · Historia
Como público objetivo, quiero leer el contexto de la operación "After The Storm", para decidir si la temática me interesa.
**Criterios de aceptación**
- Texto claro, sin errores ortográficos.
- Tono serio y respetuoso.
- No revela finales ni giros importantes.

### US-05 · Personajes
Como jugador interesado, quiero conocer a los personajes principales, para conectar con la historia.
**Criterios de aceptación**
- Cada personaje tiene nombre, rol, descripción corta e imagen (con `alt`).
- Se presentan en tarjetas ordenadas.
- Se adaptan a pantallas pequeñas (1 columna en móvil).

### US-06 · Black Studios
Como estudiante, quiero conocer al estudio y su equipo, para entender quién desarrolla el juego.
**Criterios de aceptación**
- Breve descripción del estudio.
- Se muestran integrantes o logo.
- Se ubica junto al formulario de contacto.

### US-07 · Diseño responsive
Como jugador casual, quiero que la página se vea bien en mi celular, para consultarla desde cualquier lugar.
**Criterios de aceptación**
- Se ve correctamente en 360 px, 768 px y 1280 px.
- Sin scroll horizontal.
- Textos legibles y botones táctiles de al menos 44 px.

### US-08 · Accesibilidad
Como usuario con discapacidad visual o motriz, quiero navegar con teclado y lector de pantalla, para acceder al mismo contenido que los demás.
**Criterios de aceptación**
- Contraste mínimo AA (4.5:1).
- Imágenes con texto alternativo.
- Orden lógico de encabezados y foco visible.

### US-09 · Menú fijo

Como visitante, quiero que el menú siga visible al bajar, para no tener que subir al inicio. Criterios de aceptación
**Criterios de aceptación**
- Header fijo sin tapar el contenido.
- Resalta la sección activa.

### US-10 · Noticias
Como compañero de carrera o jugador, quiero ver las novedades del desarrollo, para saber cuándo habrá DEMO. Criterios de aceptación

**Criterios de aceptación**
- Cada noticia tiene fecha y título.
- Se ordenan de la más reciente a la más antigua.
- Se muestra mensaje sobre la próxima DEMO.

## Definition of Done (hecho)

Una historia se considera terminada cuando:

- Cumple todos sus criterios de aceptación.
- El HTML valida sin errores (W3C Validator).
- Se ve bien en móvil, tablet y escritorio.
- Se probó en al menos 2 navegadores (Chrome y Firefox).
- No hay errores ortográficos.
- Fue revisada por otro integrante del equipo.
