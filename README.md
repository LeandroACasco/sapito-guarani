# 🐸 Sapito Guaraní — Roguelike Edition

> **Aprendé guaraní jugando.** Un juego educativo con mecánicas roguelike, sistema de cartas, logros, niveles, pronunciación real en guaraní y funciones sociales online.

---

## 🎮 [▶ JUGAR AHORA](https://LeandroACasco.github.io/sapito-guarani/)

---

## ✨ ¿Qué es Sapito Guaraní?

Un juego de preguntas y respuestas sobre la lengua guaraní, pensado para aprender de forma divertida. Cada partida es diferente gracias al sistema de cartas roguelike — elegís potenciadores, construís tu estrategia y tratás de llegar al puntaje perfecto. Con funciones sociales para jugar y aprender con amigos.

---

## 🃏 Características

| | |
|---|---|
| 🧠 | **3 niveles de dificultad** — Básico, Intermedio y Avanzado |
| 📚 | **6 temas** — Saludos, Números y Colores, Animales y Naturaleza, Gramática, Comidas paraguayas, Familia y cuerpo humano |
| 🃏 | **Sistema de cartas roguelike** — Elegí entre cartas únicas cada partida |
| 🔊 | **Pronunciación guaraní real** — TTS entrenado específicamente en guaraní (Meta MMS) |
| 📅 | **Frase del día** — Una expresión guaraní nueva cada día (pool ampliado con frases culturales) |
| 👂 | **Modo Escuchá y Elegí** — Reconocé palabras al oído |
| 🔤 | **Modo Conjugación** — Practicá los prefijos verbales (a-, re-, o-, ro-, ja-, pe-) con 8 verbos |
| 🎵 | **Sección Cultura Guaraní** — Poesía oral, refranes tradicionales y conceptos filosóficos |
| 🏆 | **22 logros desbloqueables** |
| ⭐ | **Sistema de XP y niveles** (1–10) con desbloqueos progresivos |
| 🎨 | **Cosméticos y skins** para tu sapito (11 variantes) |
| 🌦️ | **Sistema de clima** dinámico según la hora del día |
| 📬 | **Modo Postal** — Generá una postal personalizada con tu progreso |
| 🔥 | **Multiplicador de racha** — x2 y x3 por respuestas consecutivas |
| 💊 | **Sistema de energía** — Agua y comida para mantener a tu sapito activo |
| 🎒 | **Inventario** con consumibles |
| 😊 | **Sistema de humor** — Tu sapito reacciona según tu desempeño |

---

## 📚 Contenido del juego

### Temas de preguntas (6 temas, ~150 preguntas en total)

- **👋 Saludos** — Formas de saludar, despedirse y presentarse en guaraní paraguayo auténtico.
- **🔢 Números y colores** — Del 1 al 100 y colores básicos.
- **🐾 Animales y naturaleza** — Fauna y flora local con vocabulario guaraní.
- **📚 Gramática** — Prefijos, sufijos, estructura de la lengua, clases de verbos y fenómenos fonológicos.
- **🌿 Comidas paraguayas** — Chipa, mbejú, sopa paraguaya, tereré, mandi'o, ka'a he'ẽ, so'o josopy y más. Con contexto cultural.
- **👨‍👩‍👧 Familia y cuerpo humano** — Sy, túva, reindy, mitã, angirũ; akã, hesa, po, py'a. Incluye el significado filosófico de py'a y ñemoñare.

### Modo Conjugación 🔤

Practicá los 6 prefijos verbales del guaraní con 8 verbos comunes:

| Prefijo | Persona |
|---|---|
| a- | Yo |
| re- | Vos / Tú |
| o- | Él / Ella |
| ro- | Yo y vos |
| ja- | Nosotros (todos) |
| pe- | Ustedes |

Verbos incluidos: *karu* (comer), *ho* (ir), *japo* (hacer), *moñe'ẽ* (hablar/leer), *hai* (escribir), *porandu* (preguntar), *'u* (comer/beber), *ky'a* (ensuciarse).

### Sección Cultura Guaraní 🎵

Contenido organizado en tres pestañas:

- **🌿 Poesía** — 6 fragmentos de tradición oral guaraní con traducción y contexto. Con audio TTS.
- **💬 Dichos** — 7 refranes populares sobre la comunidad, la naturaleza y la sabiduría guaraní.
- **🌍 Cosmovisión** — 6 conceptos filosóficos: *teko* (modo de ser), *ñe'ẽ* (palabra/alma), *py'a* (corazón/ánimo), *yvy marane'ỹ* (la tierra sin mal), *jopara* (la mezcla viva), *ava* (persona guaraní).

---

| | |
|---|---|
| 🔐 | **Registro e inicio de sesión** con email y contraseña |
| 🏆 | **Tabla de líderes global** — Top 20 jugadores por XP total |
| 🏅 | **Liga Semanal** — Ranking que se resetea cada lunes, con temporadas |
| 📣 | **Feed de actividad** — Logros, subidas de nivel, rachas y regalos de tus amigos en tiempo real |
| 👥 | **Sistema de amigos** — Buscá, agregá y quitá amigos |
| ⚔️ | **Desafíos 1v1** — Retá a un amigo a superar tu puntaje, con 24hs de vigencia |
| 🎁 | **Regalos** — Mandá agua o comida a un amigo una vez por día; se suman al inventario |
| 📊 | **Perfil detallado de amigos** — Stats, logros, skins y comparación directa |
| 💬 | **Feedback para testers** — Comentarios categorizados en tiempo real |
| 📈 | **Estadísticas globales** — Jugadores totales, partidas, preguntas más falladas |
| 🔄 | **Sincronización automática** de XP, nivel, racha y liga semanal a la nube |

---

## 🔥 Colecciones Firestore

| Colección | Descripción |
|---|---|
| `players/{uid}` | Perfil del jugador: XP, nivel, racha, logros, skins |
| `liga/{week_uid}` | XP semanal por jugador para la Liga Semanal |
| `activity/{doc}` | Feed de actividad: logros, niveles, rachas, regalos, desafíos |
| `desafios/{doc}` | Desafíos 1v1 entre amigos (expiran en 24hs) |
| `regalos/{doc}` | Regalos de agua/comida entre amigos |
| `feedback/{doc}` | Comentarios y sugerencias de testers |
| `wrongAnswers/{key}` | Preguntas más falladas globalmente |

---

El juego usa el modelo **[joselobenitezg/mms-grn-tts](https://huggingface.co/joselobenitezg/mms-grn-tts)** — un modelo VITS entrenado específicamente en guaraní por el proyecto **Meta MMS** (Massively Multilingual Speech), alojado en el Space **[bigproof2010/guarani](https://huggingface.co/spaces/bigproof2010/guarani)**. La voz es real, no una aproximación en español. Incluye fallback a Web Speech API.

---

## 📖 Precisión lingüística

Las traducciones del juego fueron revisadas y validadas utilizando las siguientes fuentes académicas:

### Bibliografía principal (guaraní paraguayo)

- **Guasch, Antonio, S.J.** (1996). *Diccionario Castellano-Guaraní / Guaraní-Castellano*. Asunción, Paraguay. La referencia académica más importante del guaraní paraguayo, digitalizada en [Portal Guaraní](https://www.portalguarani.com).

- **MITIC / Secretaría de Políticas Lingüísticas del Paraguay** (2020). *Ñe'ẽryru Guarani–Español / Español–Guaraní*. Diccionario oficial del gobierno paraguayo, con ~15.000 palabras. Disponible en: [paraguay.gov.py](https://www.paraguay.gov.py/traductor-guarani)

- **Cañete, Oscar Mauricio** (2022). *Diccionario Guaraní–Español–Inglés (Aragua Avañe'ẽ)*. Encarnación, Paraguay. Disponible en: [Portal Guaraní](https://portalguarani.com/3249_oscar_mauricio_canete/25309_diccionario__guarani_espanol_ingles__por_oscar_mauricio_canete.html)

> El juego usa exclusivamente las formas del guaraní paraguayo auténtico: *Mba'éichapa ne ko'ê* (buenos días), *Mba'éichapa nde ka'aru* (buenas tardes), *Mba'éichapa ndepyhare* (buenas noches) y *Maitei* (saludo universal), según las fuentes académicas paraguayas citadas.

### Notas ortográficas

El juego utiliza la ortografía normalizada post-1950:
- Tilde nasal para vocales nasales: **ã, ẽ, ĩ, õ, ũ**
- Apóstrofo `'` (puso) para la interrupción glotal intervocálica
- **K** en reemplazo de C/Q (ej: *karu*, no *caru*)
- **H** en reemplazo de JH (ej: *hovy*, no *jhovy*)
- **V** en reemplazo de B (ej: *yvoty*, no *yboty*)

---

## 🛠️ Tecnología

- HTML5 / CSS3 / JavaScript vanilla — sin frameworks ni bundlers
- Canvas API para el modo postal
- Web Speech API (fallback TTS)
- HuggingFace Spaces + Gradio 5 para TTS guaraní real
- Firebase Authentication + Firestore para funciones online
- GitHub Pages para hosting estático

---

## 🇵🇾 Sobre el guaraní

El guaraní es una lengua indígena hablada principalmente en Paraguay, donde es lengua oficial junto al español. Es hablado por más de 6 millones de personas en toda Sudamérica. Este proyecto busca contribuir a su difusión y aprendizaje de forma accesible y entretenida. **Hecho con 💚 en Paraguay.**

---

## 📄 Créditos y Licencia

© 2026 [LeandroACasco](https://github.com/LeandroACasco) — Uso libre para fines educativos.

- TTS: [bigproof2010/guarani](https://huggingface.co/spaces/bigproof2010/guarani) · Modelo: [joselobenitezg/mms-grn-tts](https://huggingface.co/joselobenitezg/mms-grn-tts)
- Backend online: [Firebase](https://firebase.google.com) (Google)
- Desarrollado con [Claude](https://claude.ai) (Anthropic)
