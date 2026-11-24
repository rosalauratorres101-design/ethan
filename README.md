# Ethan · Aprende y Juega

App bilingüe (español e inglés) para aprender jugando, de PreK a 8.º grado.
Creada por **Rosa Laura Torres**, maestra de español en Austin, Texas.

*Bilingual (Spanish/English) learning app for PreK through 8th grade. English summary at the bottom.*

## Qué tiene

- **4 niveles:** PreK–Kínder, 1.º–2.º, 3.º–5.º y 6.º–8.º.
- **94 lecciones en 14 materias:** lectura, gramática, vocabulario, matemáticas, álgebra, geometría, escuchar, hablar, escritura, comparar lecturas, cultura, ciencias, biología y geografía. Cada nivel tiene un botón para filtrar por materia.
- **Alineada a los estándares:** cada lección está revisada contra Common Core y NGSS (Washington y la mayoría de los estados), los TEKS de Texas y las Bases Curriculares de Chile. La lista completa está en [ALINEACION.md](ALINEACION.md) y dentro de la app, en *Para padres y maestros › Estándares*.
- **La práctica sube de nivel sola:** empieza con lo que piden todos los programas y avanza conforme el niño acierta (por ejemplo, sumas de dos dígitos y luego de tres).
- **Diferenciación en tres niveles:** en *Para padres y maestros* se elige Simplificado (dos opciones por pregunta, lectura en voz alta, explicación corta), Estándar o Avanzado (más difícil y con retos del siguiente nivel).
- **Hojas de trabajo para imprimir:** el maestro elige nivel, lección, diferenciación (Simplificado, Estándar o Avanzado) e idioma (español o inglés), y la app crea una hoja nueva cada vez, con clave de respuestas y guía del maestro (objetivo, estándares, materiales y actividad de 25 a 35 minutos). Hay guía para todas las lecciones: matemáticas, español, geografía, ciencias y cultura. Se imprime o se guarda como PDF, sin internet.
- **Corrector de textos:** en la escritura libre, el botón *Revisar y corregir* señala mayúsculas, puntos, signos ¿? ¡!, palabras repetidas y errores comunes de ortografía. El niño decide qué cambios acepta. Funciona sin internet y sin IA.
- **Cada lección va en 4 pasos:** instrucciones, explicación, ejemplos y ejercicios. Las de escritura traen un quinto paso de escritura libre.
- **Ejercicios sin fin:** la práctica no se acaba; la app crea preguntas nuevas mientras el niño quiera seguir. Cada bloque de 5 cuenta para su progreso.
- **Tipos de ejercicio:** opción múltiple, preguntas en audio (con la opción de ver el texto), dictado de palabras y números, ordenar letras y palabras, escribir la respuesta (avisa si falta un acento), práctica oral con autoevaluación y escritura libre con lista de revisión.
- **Lecturas por nivel**, incluidas lecturas de comparación lado a lado con su tabla.
- **Tu búho crece:** cada lección pasa de 🥚 Huevito a 🐣 Pollito, 🐦 Ya vuela y 🦉 Búho sabio. Hay pistas en cada pregunta, un gran reto por grado y una página de progreso.
- **Actividades para los más pequeños:** abecedario, sílabas, familias de palabras en inglés, números, colores y 4 juegos.
- **Tres modos de idioma:** Español, English o los dos a la vez.
- **Para Estados Unidos o cualquier país hispanohablante:** al abrir la app (o en *Para padres y maestros*) se elige el país entre Estados Unidos, Puerto Rico y los 20 países donde el español es oficial. La app cambia las ciudades de los ejemplos y de las oraciones para ordenar, la pregunta del hemisferio, agrega la nota de *vosotros* (España) o de *vos* (Argentina, Uruguay, Paraguay y Centroamérica) y busca en el aparato una voz con el acento de ese país.
- **Sonido:** música de fondo original (se baja sola cuando habla la voz) y efectos al acertar, al ganar estrellas y al cambiar de página. Hay botones 🔊 y 🎵 arriba para apagarlos.
- **Voz humana:** en el estudio de grabación un adulto graba cada frase y los niños oyen esa voz. El modo *Grabación continua* detecta cuando terminas de hablar, guarda y pasa sola a la siguiente frase. Lo que todavía no se ha grabado usa la voz del aparato; en *Para padres y maestros* se elige la voz más natural y la velocidad.

## Privacidad de los niños

La app no pide datos personales, no tiene cuentas, anuncios ni enlaces externos, y no se conecta a otros sitios. Los detalles están en [PRIVACY.md](PRIVACY.md).

## Cómo publicarla en GitHub (paso a paso)

1. Entra a github.com con tu cuenta y toca **New** (nuevo repositorio).
2. Ponle de nombre `ethan-app`, elige **Public** y toca **Create repository**.
3. Toca el enlace **uploading an existing file**.
4. Arrastra **todo lo que hay dentro** de la carpeta `ethan-app`: `index.html`, `sw.js`, `manifest.webmanifest`, `README.md`, `PRIVACY.md`, `LICENSE` y las carpetas `icons` y `voces`.
5. Abajo, toca **Commit changes**.
6. Ve a **Settings › Pages**. En *Branch* elige `main` y `/ (root)`, y toca **Save**.
7. Espera uno o dos minutos. Tu app va a quedar en:
   `https://TU-USUARIO.github.io/ethan-app/`

## Cómo abrirla e instalarla

Funciona en cualquier sistema con un navegador de 2020 en adelante: **Chrome**, **Edge** o **Firefox** (Android, Chromebook, Windows, Mac, Linux) y **Safari** (iPhone, iPad y Mac). También se puede abrir directo como archivo (`index.html`) en una laptop, sin internet. Ábrela siempre en el navegador, no dentro de otra app: el visor de la app de Claude en Android, por ejemplo, no trae voz.

- **Android:** abre el enlace en Chrome, toca el menú ⋮ y luego **Instalar app** o **Agregar a la pantalla principal**.
- **Laptop o Chromebook:** abre el enlace en Chrome o Edge y toca el ícono de instalar en la barra de direcciones.
- **iPhone o iPad:** abre el enlace en Safari, toca **Compartir** y luego **Agregar a pantalla de inicio**.

Al abrir la app aparece el botón **Toca para empezar**, que activa el sonido. Si la voz no se oye, ve a *Para padres y maestros* y toca **Prueba de sonido**: te dice exactamente qué falla.

Para una voz más natural, descarga las voces del aparato:
- **Android:** Ajustes › Accesibilidad › Texto a voz.
- **iPad o iPhone:** Ajustes › Accesibilidad › Contenido leído › Voces (elige una «Mejorada» o «Premium»).
- **Windows:** Configuración › Hora e idioma › Voz.

## Cómo grabar las voces

1. En la app, toca **Para padres y maestros** y contesta la multiplicación del candado.
2. Toca **Estudio de grabación** y elige un grupo (por ejemplo, *ABC en español*).
3. Toca **Grabar**, lee la frase, toca **Parar**, escúchala y toca **Guardar**. La app pasa sola a la siguiente frase.
4. Cuando termines un grupo, toca **Exportar voces**. Se descarga el archivo `voces.json`.
5. En GitHub, entra a la carpeta `voces`, toca **Add file › Upload files**, sube tu `voces.json` (reemplaza al que está) y toca **Commit changes**.
6. Desde ese momento, todos los que abran la app oyen tu voz.

Para que el micrófono funcione, la app tiene que estar abierta desde su enlace de GitHub (https).

## Créditos

- Contenido, diseño pedagógico y voces: Rosa Laura Torres.
- El código se escribió con ayuda de una herramienta de IA (Claude, de Anthropic), bajo la dirección y revisión de la autora.
- Los dibujos de la app son emojis del sistema y gráficos SVG originales hechos para esta app.
- Todo el contenido, los personajes, los nombres y el diseño son originales. Ethan no está afiliado a ninguna otra plataforma educativa.

---

## English summary

Ethan is a bilingual Spanish/English learning app for PreK–8. It has 94 lessons across 14 subjects (reading, grammar, vocabulary, math, algebra, geometry, listening, speaking, writing, text comparison, culture, science, biology and geography), each with instructions, an explanation, examples and endless practice. Exercise types include multiple choice, audio questions, dictation, word ordering, typed answers with accent feedback, speaking practice and free writing with a checklist. Each lesson's owl grows as the child improves, and there are hints, a grade challenge and a progress page. Families choose their country (United States, Puerto Rico or any of the 20 Spanish-speaking countries): the app adapts example cities, the hemisphere question, adds vosotros/vos notes where they're used, and prefers a device voice with that country's accent. Every lesson is aligned to Common Core/NGSS, Texas TEKS and Chile's national curriculum (see [ALINEACION.md](ALINEACION.md)); practice difficulty rises automatically, and free writing includes an offline, rule-based checker (no AI). An adult can record every phrase in the built-in recording studio so children hear a real human voice. The app collects no personal data, has no accounts, ads or outside links, and works offline. See [PRIVACY.md](PRIVACY.md).

All content, characters, names and design are original. Ethan is not affiliated with any other educational platform.

To publish: create a public repo, upload all files, then turn on **Settings › Pages** (branch `main`, root folder).


---

## Ethan for Teachers (English) — #BuildHybridAI 2026

**Live page:** https://rosalauratorres101-design.github.io/ethan/maestros.html

Ethan is a free bilingual (Spanish/English) PreK–8 learning app for children. The children's app (`index.html`) has **no AI and makes no network calls**. Its Content Security Policy blocks every external connection.

**Ethan for Teachers** (`maestros.html`) is a separate page for adults only. It uses **Firebase AI Logic hybrid inference** to help teachers adapt Ethan's lessons for their own class:

- **Leveled reading:** a short reading on the lesson topic, at the grade level and differentiation level the teacher picks (Simplified, Standard or Advanced).
- **Re-explain a lesson:** a new explanation and examples for students who did not get it the first time.
- **Writing feedback:** feedback on a student's paragraph. This mode runs **only on the device** (Gemini Nano) when it is available, so student writing never leaves the computer.
- **Practice questions:** new questions with an answer key, ready to print.
- Material in **Spanish or English**, with names and places adapted to the teacher's country.

### How Firebase AI Logic is used

- `getGenerativeModel` with `InferenceMode.PREFER_ON_DEVICE` (Gemini Nano in Chrome, cloud `gemini-3.5-flash-lite` as fallback), `ONLY_ON_DEVICE` for student writing, and `ONLY_IN_CLOUD` when the teacher chooses it.
- Every result shows where it ran (`inferenceSource`): on the device or in the cloud.
- **App Check** with reCAPTCHA Enterprise protects the API.
- Before any text is sent, a privacy filter removes names, emails and phone numbers.
- In hybrid mode, if Gemini Nano takes longer than 2 minutes, the page switches to the cloud. If the cloud is busy, it waits and retries up to 3 times.
- After every answer, an automatic check fixes Spanish ¡ and ¿ marks and sentence capitals, removes vocabulary words that are not in the reading, and drops broken questions. It tells the teacher what it changed. The teacher still reviews everything before class.
- If there is no internet and no on-device model, the page still shows Ethan's own lesson material (no AI).

### Run it

1. Open the live page in Chrome on a computer (Gemini Nano needs desktop Chrome).
2. To run your own copy, put your Firebase web config in `maestros.html`, enable Firebase AI Logic (Gemini Developer API) and App Check, and serve the folder with any static server, for example `python3 -m http.server`.

### Why it matters

Teachers in bilingual and dual-language classrooms spend hours adapting material to different reading levels and two languages. Ethan for Teachers does it in under a minute, keeps student data private, and keeps AI away from children.

License: MIT (see `LICENSE`).
