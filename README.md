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
| 📚 | **4 temas** — Saludos, Números y Colores, Animales y Naturaleza, Gramática |
| 🃏 | **Sistema de cartas roguelike** — Elegí entre cartas únicas cada partida |
| 🔊 | **Pronunciación guaraní real** — TTS entrenado específicamente en guaraní (Meta MMS) |
| 📅 | **Frase del día** — Una expresión guaraní nueva cada día |
| 👂 | **Modo Escuchá y Elegí** — Reconocé palabras al oído |
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

## 🌐 Funciones Online (Firebase)

| | |
|---|---|
| 🔐 | **Registro e inicio de sesión** con email y contraseña |
| 🏆 | **Tabla de líderes global** — Top 20 jugadores por XP |
| 👥 | **Sistema de amigos** — Buscá, agregá y quitá amigos |
| 📊 | **Perfil detallado de amigos** — Stats, logros, skins y comparación directa |
| 💬 | **Feedback para testers** — Comentarios categorizados en tiempo real |
| 📈 | **Estadísticas globales** — Jugadores totales, partidas, preguntas más falladas |
| 🔄 | **Sincronización automática** de XP, nivel y racha a la nube |

---

## 🗣️ Pronunciación guaraní real

El juego usa el modelo **[joselobenitezg/mms-grn-tts](https://huggingface.co/joselobenitezg/mms-grn-tts)** — un modelo VITS entrenado específicamente en guaraní por el proyecto **Meta MMS** (Massively Multilingual Speech), alojado en el Space **[bigproof2010/guarani](https://huggingface.co/spaces/bigproof2010/guarani)**. La voz es real, no una aproximación en español. Incluye fallback a Web Speech API.

---

## 📖 Precisión lingüística

Las traducciones del juego fueron revisadas y validadas utilizando las siguientes fuentes académicas:

### Bibliografía principal (guaraní paraguayo)

- **Guasch, Antonio, S.J.** (1996). *Diccionario Castellano-Guaraní / Guaraní-Castellano*. Asunción, Paraguay. La referencia académica más importante del guaraní paraguayo, digitalizada en [Portal Guaraní](https://www.portalguarani.com).

- **MITIC / Secretaría de Políticas Lingüísticas del Paraguay** (2020). *Ñe'ẽryru Guarani–Español / Español–Guaraní*. Diccionario oficial del gobierno paraguayo, con ~15.000 palabras. Disponible en: [paraguay.gov.py](https://www.paraguay.gov.py/traductor-guarani)

- **Cañete, Oscar Mauricio** (2022). *Diccionario Guaraní–Español–Inglés (Aragua Avañe'ẽ)*. Encarnación, Paraguay. Disponible en: [Portal Guaraní](https://portalguarani.com/3249_oscar_mauricio_canete/25309_diccionario__guarani_espanol_ingles__por_oscar_mauricio_canete.html)

### Bibliografía complementaria (guaraní correntino)

- **Ministerio de Educación de la Provincia de Corrientes** (2022). *Avañe'ẽ del Taragui: Diccionario guaraní-español / español-guaraní*. Coordinación de Educación Intercultural Bilingüe. ISBN 978-987-48916-3-1. Disponible en: [mec.gob.ar](https://www.mec.gob.ar/descargas/Documentos/Educacion%20Intercultural%20Bilingue/GUARANI/avane-Diccionario-Guarani-Esp-Esp-Guarani.pdf)

> **Nota:** El juego prioriza las formas del guaraní paraguayo estándar (p. ej. *Pyhareve*, *Ka'aruma*, *Pytumia*, *Maitei*) sobre las variantes correntinas (*Ko'ê porã*, *Ka'aru porã*, *Pytû porã*), aunque ambas se incluyen en el diccionario in-game con su respectiva nota de variante.

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

El guaraní es una lengua indígena hablada principalmente en Paraguay, donde es lengua oficial junto al español, y en la provincia de Corrientes (Argentina), donde fue declarada idioma oficial alternativo por la Ley Provincial Nº 5.598 (2004). Es hablado por más de 6 millones de personas en toda Sudamérica. Este proyecto busca contribuir a su difusión y aprendizaje de forma accesible y entretenida. **Hecho con 💚 en Paraguay.**

---

## 📄 Créditos y Licencia

© 2026 [LeandroACasco](https://github.com/LeandroACasco) — Uso libre para fines educativos.

- TTS: [bigproof2010/guarani](https://huggingface.co/spaces/bigproof2010/guarani) · Modelo: [joselobenitezg/mms-grn-tts](https://huggingface.co/joselobenitezg/mms-grn-tts)
- Backend online: [Firebase](https://firebase.google.com) (Google)
- Desarrollado con [Claude](https://claude.ai) (Anthropic)
