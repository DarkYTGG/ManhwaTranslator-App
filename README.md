<div align="center">

  <img src="assets/app_logo.png" alt="Manhwa AI Translator Logo" width="130" height="130" style="border-radius: 24px; box-shadow: 0 8px 24px rgba(0,0,0,0.25);" />

  # ⚡ Manhwa AI Translator
  ### Traductor en Tiempo Real con IA para Cómics, Manhwas, Mangas, Novelas Web y Apps

  **Nivel Scanlation Profesional en tu Pantalla · Inpainting Inteligente · Tipografías de Cómic**

  <p align="center">
    <a href="https://github.com/DarkYTGG/ManhwaTranslator-App/releases/latest">
      <img src="https://img.shields.io/github/v/release/DarkYTGG/ManhwaTranslator-App?color=7C3AED&label=%C3%9Altima%20Versi%C3%B3n&logo=android&style=for-the-badge" alt="Última Versión">
    </a>
    <a href="https://github.com/DarkYTGG/ManhwaTranslator-App/stargazers">
      <img src="https://img.shields.io/github/stars/DarkYTGG/ManhwaTranslator-App?color=F59E0B&logo=reverbnation&logoColor=white&style=for-the-badge" alt="GitHub Stars">
    </a>
    <a href="https://github.com/DarkYTGG/ManhwaTranslator-App/releases">
      <img src="https://img.shields.io/github/downloads/DarkYTGG/ManhwaTranslator-App/total?color=10B981&logo=googleplay&logoColor=white&style=for-the-badge" alt="Descargas">
    </a>
    <a href="https://github.com/DarkYTGG">
      <img src="https://img.shields.io/badge/Autor-%40DarkYTGG-2563EB?logo=github&style=for-the-badge" alt="Autor DarkYTGG">
    </a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Android-8.0%2B%20(API%2026--35)-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android">
    <img src="https://img.shields.io/badge/Kotlin-2.0-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
    <img src="https://img.shields.io/badge/Jetpack-Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white" alt="Compose">
    <img src="https://img.shields.io/badge/OCR-Google%20ML%20Kit-FBBC04?style=flat-square&logo=google&logoColor=black" alt="ML Kit">
    <img src="https://img.shields.io/badge/IA-Gemini%20%7C%20GPT--4o%20%7C%20DeepSeek-9333EA?style=flat-square&logo=openai&logoColor=white" alt="AI Providers">
    <img src="https://img.shields.io/badge/Licencia-MIT-10B981?style=flat-square" alt="Licencia">
  </p>

  <p align="center">
    <a href="https://github.com/DarkYTGG/ManhwaTranslator-App/releases/latest/download/ManhwaTranslator.apk">
      <b>📥 Descargar APK Directa (Gratis)</b>
    </a>
    •
    <a href="#caracteristicas">✨ Características</a>
    •
    <a href="#comparativa">📊 Comparativa</a>
    •
    <a href="#instalacion">🚀 Instalación</a>
    •
    <a href="#otros-proyectos">🌟 Otros Proyectos</a>
  </p>

</div>

---

## 📖 Tabla de Contenidos

1. [🌟 ¿Qué es Manhwa AI Translator?](#que-es)
2. [📊 Comparativa: Manhwa AI Translator vs. Traductores Convencionales](#comparativa)
3. [✨ Características Principales](#caracteristicas)
4. [🛠️ Arquitectura Técnica y Flujo de Procesamiento](#arquitectura)
5. [🌍 Idiomas y Dialectos Soportados](#idiomas)
6. [📲 Instalación y Primeros Pasos](#instalacion)
7. [🔑 Configurar tu Clave Gratuita de Google Gemini](#configuracion-gemini)
8. [🌐 Más Proyectos Destacados de @DarkYTGG](#otros-proyectos)
9. [💻 Tecnologías y Stack Utilizado](#tecnologias)
10. [🤝 Contribuir y Soporte](#soporte)

---

<a id="que-es"></a>
## 🌟 ¿Qué es Manhwa AI Translator?

**Manhwa AI Translator** es una aplicación nativa para Android diseñada específicamente para lectores exigentes de cómics coreanos (*Manhwas/Webtoons*), japoneses (*Mangas*), chinos (*Manhuas*), novelas ligeras en inglés, videojuegos y aplicaciones móviles.

A diferencia de las herramientas genéricas que colocan cuadros toscos de texto que arruinan el dibujo, Manhwa AI Translator funciona como un **asistente de Scanlation automatizado en tiempo real**:

- **Detecta con precisión** los globos de diálogo individuales o conectados.
- **Aplica inpainting limpio**, borrando el texto original con el color exacto del fondo de la viñeta.
- **Tipografía real de cómic**, calculando matemáticamente el tamaño y corte de línea para que las letras encajen dentro del globo de forma estética y natural.
- **Traducción contextual con IA**, evitando errores de género, conservando modismos y respetando honoríficos propios de la cultura oriental (*Hyung, Oppa, Senpai, Shifu*).

---

<a id="comparativa"></a>
## 📊 Comparativa vs Otros Traductores

| Característica | ⚡ Manhwa AI Translator | 🔍 Google Lens | 📱 Traductores Genéricos |
| :--- | :---: | :---: | :---: |
| **Inpainting Limpio (Sin recuadros feos)** | ✅ **100% Sólido Subpíxel** | ❌ Borroso / Parche gris | ❌ Cajas opacas con bordes |
| **Tipografía Real de Cómic (`Comic Neue`, `Bangers`)** | ✅ **Nivel Editorial** | ❌ Fuente genérica del sistema | ❌ Arial / Roboto plana |
| **Ajuste Dinámico de Burbuja (Binary Search Sizing)** | ✅ **Alineación perfecta** | ❌ Desbordes frecuentes | ❌ Texto cortado o diminuto |
| **Comprensión Contextual y Memoria de Escena** | ✅ **IA Multimodal (LLMs)** | ❌ Traducción aislada palabra a palabra | ❌ Literal sin coherencia |
| **Lectura Manga Derecha a Izquierda (RTL) y Vertical** | ✅ **Soporte Completo** | ❌ Solo lectura occidental | ⚠️ Fallos frecuentes |
| **Glosario Personalizado (Nombres y Términos)** | ✅ **Totalmente Editable** | ❌ No disponible | ❌ No disponible |
| **Navegador Web Integrado con AdBlock** | ✅ **Incluido** | ❌ No | ❌ No |
| **Traducción 100% Gratuita (Google AI Studio)** | ✅ **Gemini 1.5 Flash sin límites** | ⚠️ Requiere conexión a Google | 💳 Planes de pago o anuncios |
| **Actualizaciones Automáticas Integradas (OTA)** | ✅ **En 1 clic desde la App** | ⚠️ Requiere Play Store | ❌ Descargas manuales |

---

<a id="caracteristicas"></a>
## ✨ Características Principales

### 🔮 1. Modo Universal Inteligente
Clasifica de manera automática el elemento visual en pantalla y ajusta el estilo de renderizado sin que tengas que tocar nada:
- **Globos de diálogo:** Centrado elíptico con tipografía `Comic Neue Bold` y márgenes proporcionales.
- **Gritos y efectos de impacto:** Fuente `Bangers Regular` en mayúsculas de alto contraste.
- **Novelas Web y textos largos:** Bloques de lectura continua optimizados para evitar fatiga visual.
- **Interfaces de juegos o apps de mensajería:** Tarjetas minimalistas con detección y descarte de elementos de UI (batería, hora, botones del sistema).

### 🎨 2. Tipografías Profesionales Integradas
Olvídate de fuentes genéricas y textos deformados. La app incluye tipografías vectoriales calibradas:
- 💬 **`Comic Neue Bold`**: Diálogos editoriales limpios y de alta legibilidad.
- 💥 **`Bangers Regular`**: Momentos de acción, gritos de combate, onomatopeyas y exclamaciones.
- 💭 **`Comic Neue Italic`**: Monólogos internos, susurros y pensamientos de personajes.
- 📖 **`Prose & Modern Sans`**: Interfaces de usuario, menús de videojuegos y párrafos descriptivos.

### 🧼 3. Inpainting Sólido y Respeto al Arte
- Muestreo cromático inteligente para replicar el fondo exacto del globo o de la viñeta.
- Cobertura total de la tinta original sin recortar los trazos del dibujo circundante.
- Soporte completo para pantallas con notch, esquinas redondeadas y barras dinámicas de Android.

### 🌐 4. Navegador Web Integrado con AdBlocker
- Lee directamente en agregadores o sitios oficiales de mangas y manhwas.
- **AdBlocker Nativo:** Bloquea ventanas emergentes, scripts de redirección y publicidad invasiva.
- **Traductor de Capítulos en Cascada:** Descarga y traduce capítulos completos página a página para leer fluidamente sin pausas.

### 🤖 5. Arquitectura Multi-Motor de IA Flexible
Elige el motor de IA que prefieras según tu velocidad de conexión o preferencia:
- **Google Gemini (1.5 Flash / 1.5 Pro):** Ultra veloz, compresión de contexto superior y **100% gratuito** mediante tu API de Google AI Studio.
- **OpenAI (GPT-4o / GPT-4o-mini):** Máxima precisión de redacción y localización narrativa.
- **DeepSeek (DeepSeek-Chat / V3):** Gran desempeño y relación costo-eficiencia.
- **Servidor Local (Ollama / Python):** Ejecuta modelos abiertos en tu propia PC mediante red local.
- **ML Kit On-Device (Offline):** Traducción de emergencia sin necesidad de conexión a internet.

---

<a id="arquitectura"></a>
## 🛠️ Arquitectura Técnica y Flujo de Procesamiento

El pipeline fue construido con foco en **cero congelamiento del hilo principal (`0ms UI Jank`)** y bajo consumo de batería en sesiones prolongadas:

```mermaid
flowchart LR
    A["📱 Captura en Pantalla\n(MediaProjection / VirtualDisplay)"] --> B["🔍 OCR Inteligente\n(Google ML Kit Multi-Language)"]
    B --> C["🧩 Detector de Globos\n(Heurísticas RTL / Fusión / Filtro UI)"]
    C --> D["🤖 Motor de IA + Memoria\n(Gemini / OpenAI / Diccionario Scan)"]
    D --> E["📐 Motor de Tipografía\n(Binary Search Font Fit)"]
    E --> F["🎨 Overlay en Hardware Canvas\n(Inpainting Sólido Subpíxel)"]
```

1. **`ScreenCaptureEngine`**: Captura fotogramas a resolución nativa reciclando buffers para prevenir fugas de memoria (`OutOfMemoryError`).
2. **`BubbleDetector`**: Agrupa coordenadas de texto, separa globos dobles siameses y respeta el orden de lectura según el modo (vertical para Manhwa, derecha a izquierda para Manga).
3. **`TranslationEngine` & `ContextMemory`**: Empaqueta el texto en lotes estructurados para economizar tokens y mantiene el historial de la conversación previa.
4. **`TypesetterEngine`**: Aplica búsqueda binaria de tamaño de letra y partición de líneas para rellenar de forma balanceada la forma de la burbuja.
5. **`TranslationCanvasView`**: Renderiza sobre la pantalla mediante vistas nativas en capa flotante (`WindowManager.LayoutParams.TYPE_APPLICATION_OVERLAY`).

---

<a id="idiomas"></a>
## 🌍 Idiomas y Dialectos Soportados

| Idioma Original | Idioma de Destino | Modos y Formatos Soportados |
| :--- | :--- | :--- |
| **Coreano (한국어)** | Español Latinoamericano / Castellano | Manhwas, Webtoons, Diálogos y Novelas |
| **Japonés (日本語)** | Español Latinoamericano / Castellano | Mangas (Lectura Horizontal y Vertical RTL) |
| **Chino (中文)** | Español Latinoamericano / Castellano | Manhuas, Webnovels (Xianxia/Wuxia) y Juegos |
| **Inglés (English)** | Español Latinoamericano / Castellano | Webtoons occidentales, Novelas Web y Apps |
| **Automático (Auto)** | Español Latinoamericano / Castellano | Detección inteligente por análisis Unicode |

> [!TIP]
> Puedes seleccionar entre **Español Latinoamericano** (localización neutra para cómic) y **Castellano** (España) desde el menú de ajustes de la aplicación.

---

<a id="instalacion"></a>
## 📲 Instalación y Primeros Pasos

### Paso 1: Descargar el instalador
1. Ingresa a la sección de **[Releases Oficiales](https://github.com/DarkYTGG/ManhwaTranslator-App/releases)**.
2. Descarga el archivo **`ManhwaTranslator.apk`** de la versión más reciente.
3. Abre el archivo en tu dispositivo Android y pulsa **Instalar** (permite la instalación de fuentes desconocidas si es necesario).

### Paso 2: Conceder permisos básicos
Al abrir la app por primera vez, solo necesitas otorgar:
- **Mostrar sobre otras aplicaciones:** Para poder dibujar las traducciones y el botón flotante sobre tu lector habitual (Tachiyomi, Mihon, Webtoon, Chrome, etc.).
- **Captura de pantalla (MediaProjection):** Requerido por Android para analizar las viñetas que estés leyendo en ese instante.

### Paso 3: Activar y Traducir
1. Toca en **Iniciar Servicio** en la pantalla principal.
2. Abre cualquier lector, webtoon, manga o red social.
3. Presiona el botón flotante para traducir al instante lo que esté en tu pantalla.

---

<a id="configuracion-gemini"></a>
## 🔑 Configurar tu Clave Gratuita de Google Gemini

Recomendamos usar **Google Gemini 1.5 Flash** por su impresionante velocidad y por ser **100% gratuito**:

1. Ingresa con tu cuenta de Google a **[Google AI Studio](https://aistudio.google.com/)**.
2. Haz clic en el botón azul **Get API key** y selecciona **Create API key**.
3. Copia tu clave generada.
4. En **Manhwa AI Translator**, ve a **Ajustes** ➔ **Motor de IA** ➔ Selecciona **Google Gemini**, pega tu API Key y guarda los cambios. ¡Listo!

---

<a id="otros-proyectos"></a>
## 🌐 Más Proyectos Destacados de @DarkYTGG

Si te ha resultado útil este proyecto, te invito a conocer otros desarrollos de software y herramientas de mi autoría en GitHub:

<div align="center">

| Proyecto | Tipo | Descripción | Tecnologías | Enlace |
| :--- | :---: | :--- | :---: | :---: |
| 🐓 **RoosterGenics Plugin** | 🎮 Servidores | Plugin avanzado e integral para Minecraft (Paper / Purpur / Folia 1.21) con arquitectura multihilo Folia-Aware. | ![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![PaperMC](https://img.shields.io/badge/PaperMC_1.21-02303A?style=flat-square) | [**Ver Repositorio ➔**](https://github.com/DarkYTGG/RoosterGenics-Plugin) |
| 🐓 **Wiki RoosterGenics** | 📖 Docs | Enciclopedia oficial y documentación técnica interactiva para el ecosistema de servidores de Minecraft 1.21. | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github) | [**Ver Repositorio ➔**](https://github.com/DarkYTGG/Wiki-RoosterGenics)<br>[**Demo en Vivo 🌐**](https://darkytgg.github.io/Wiki-RoosterGenics/) |
| ⚡ **IA de Respaldo** | 🎓 Académico | **Proyecto Académico:** Chatbot inteligente especializado en ingeniería eléctrica (subestaciones eléctricas, sistemas de respaldo 125 VDC y puesta a tierra). | ![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75FF?style=flat-square&logo=google) ![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | [**Ver Repositorio ➔**](https://github.com/DarkYTGG/IA-de-respaldo) |
| 🎮 **PixelVault** | 🎓 Académico | **Proyecto Académico:** Plataforma web de comercio electrónico y catálogo digital para videojuegos con diseño dinámico. | ![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask_3.1-black?style=flat-square&logo=flask) | [**Ver Repositorio ➔**](https://github.com/DarkYTGG/Tienda-de-Videojuegos) |

</div>

<p align="center">
  👉 <b>Explora todos mis repositorios en:</b> <a href="https://github.com/DarkYTGG"><b>github.com/DarkYTGG</b></a> — ¡No olvides dejar una <b>⭐ Star</b> si te gusta mi trabajo!
</p>

---

<a id="tecnologias"></a>
## 💻 Tecnologías y Stack Utilizado

- **Lenguaje:** [Kotlin 2.0](https://kotlinlang.org/) (Corrutinas, StateFlow, Serialization)
- **Framework UI:** [Jetpack Compose](https://developer.android.com/jetpack/compose) + Material 3
- **Visión Artificial:** Google ML Kit Text Recognition (Latino, Coreano, Japonés, Chino)
- **Overlay Rendering:** Android `WindowManager` con hardware canvas acelerado por GPU
- **Networking:** [OkHttp 4](https://square.github.io/okhttp/) con interceptores de reconexión y JSON seguro
- **Almacenamiento Local:** Jetpack DataStore Preferences
- **CI / CD:** GitHub Actions con compilación y publicación automatizada de versiones

---

<a id="soporte"></a>
## 🤝 Contribuir y Soporte

¡Las contribuciones de la comunidad son bienvenidas!

- 🐛 **¿Encontraste un error o bug?** Abre un reporte en la pestaña de [Issues](https://github.com/DarkYTGG/ManhwaTranslator-App/issues).
- 💡 **¿Tienes una idea o sugerencia?** Comparte tus ideas creando una discusión o un feature request.
- ⭐ **¿Te gusta el proyecto?** Dale una **estrella al repositorio** para ayudar a que más personas conozcan la aplicación.

---

<div align="center">
  <p>Creado con dedicación por <b><a href="https://github.com/DarkYTGG">@DarkYTGG</a></b> para la comunidad lectora de Manhwas, Mangas y Webtoons.</p>
  <sub>Distribuido bajo Licencia MIT. © 2026 DarkYTGG.</sub>
</div>
