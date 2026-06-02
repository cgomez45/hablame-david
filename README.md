# 🗣️ Háblame · Comunicación AAC en Español

> Aplicación de **Comunicación Aumentativa y Alternativa (CAA / AAC)** para iPad y tablets, diseñada para niños y personas no verbales que se comunican en español.

**Sin internet · Sin cuentas · Sin anuncios · Sin rastreo · Sin nube · Código abierto**

---

## ✨ ¿Qué es?

Háblame es una aplicación gratuita y de código abierto que ayuda a personas que no pueden hablar a comunicarse. El usuario selecciona íconos para construir frases, y la tablet las lee en voz alta en español.

Funciona como **Proloquo2Go**, **TD Snap**, **Grid for iPad** o **Cboard**, pero:
- ✅ Es **gratis**
- ✅ Funciona **sin internet** una vez instalada
- ✅ **No requiere App Store ni cuenta de Apple** — se instala desde el navegador
- ✅ No guarda ningún dato en la nube
- ✅ El código es abierto y puedes modificarlo

---

## 📱 Instalación en iPad (2 minutos)

### Opción A: Usar la versión publicada (más fácil)
1. Abre **Safari** en el iPad y ve a: `https://<tu-usuario>.github.io/hablame-aac/`
2. Toca el ícono de **compartir** (📤) en la barra superior.
3. Selecciona **«Agregar a pantalla de inicio»**.
4. Toca **«Agregar»**.
5. Ya está. Aparecerá un ícono nuevo en la pantalla principal. Tócalo para abrir Háblame a pantalla completa.

### Opción B: Hospedarlo tú mismo en GitHub Pages (gratis)
1. Crea una cuenta gratuita en [github.com](https://github.com).
2. Haz «fork» de este repositorio o sube los archivos a un repo nuevo.
3. Ve a **Settings → Pages**, en «Source» elige `main` y `/ (root)`. Guarda.
4. Espera 1 minuto. GitHub te dará una URL como `https://<tu-usuario>.github.io/hablame-aac/`.
5. Sigue los pasos de la Opción A con esa URL.

> 💡 También puedes abrir el archivo `index.html` localmente con doble clic — funciona, pero el reconocimiento de voz puede requerir HTTPS en algunos navegadores.

---

## 👶 Cómo usar la aplicación

### Comunicación básica
1. Toca una **categoría** (Quiero, Me siento, Comida…).
2. Toca las **palabras** que quieres usar — aparecen en la barra superior.
3. Toca el botón verde **🔊 Leer** para que la tablet lea la frase completa.
4. Usa **⌫ Borrar** para quitar la última palabra, o **🗑️ Limpiar** para empezar de nuevo.

### Categorías incluidas
- 🙋 **Quiero** — peticiones (agua, jugar, abrazo…)
- 😊 **Me siento** — emociones (feliz, triste, cansado…)
- 🍎 **Comida** — alimentos y bebidas
- 👨‍👩‍👧 **Familia** — personas
- 🚽 **Baño** — necesidades de higiene
- 🤕 **Dolor** — comunicar molestias
- 🏫 **Escuela** — vocabulario escolar
- 👍 **Sí / No** — respuestas y cortesía
- 🚨 **Emergencia** — acceso directo siempre visible

### Botón de emergencia
El botón rojo 🚨 en la esquina inferior derecha siempre está visible y lleva directamente a frases de emergencia: «ayuda, por favor», «llamen a mamá», «no puedo respirar», etc.

---

## ♿ Accesibilidad y ajustes

Toca el ícono ⚙️ (engranaje) para abrir los ajustes:

| Ajuste | Función |
|---|---|
| **Tamaño de botones** | 100 px – 240 px. Más grande = más fácil de ver/tocar/mirar |
| **Tiempo de permanencia (dwell)** | 0.5 s – 4 s. Tiempo que el cursor debe permanecer sobre un botón para activarlo |
| **Selección por permanencia** | Activa el dwell control (ver abajo) |
| **Modo escaneo** | Activa el switch scanning (ver abajo) |
| **Velocidad de escaneo** | Velocidad de avance del modo escaneo |
| **Modo alto contraste** | Fondo negro / texto blanco / acentos amarillos |
| **Leer palabra al seleccionarla** | Retroalimentación auditiva inmediata |
| **Voz** | Elige entre las voces en español disponibles en el sistema |
| **Velocidad de voz** | 0.5x – 1.5x |

### 👁️ Eye Tracking en iPadOS 18+

El **iPad** trae **Eye Tracking integrado** desde iPadOS 18 (iPad Pro y Air con chip M2 o superior, ver compatibilidad de Apple).

Para activarlo:
1. **Ajustes → Accesibilidad → Eye Tracking** (Seguimiento ocular).
2. Activa la opción y sigue el proceso de calibración (mirar puntos en la pantalla).
3. Configura **«Permanencia automática»** (Auto-Dwell) para que la mirada actúe como toque.
4. Abre Háblame. Como los botones son grandes y tienen `aria-label` correctos, **el sistema operativo manejará la selección por mirada automáticamente**.

> 💡 Si tu iPad no soporta Eye Tracking nativo, usa la opción **«Selección por permanencia»** dentro de Háblame con un cursor (Magic Mouse, trackpad, o un sistema externo de seguimiento ocular como Tobii Eye Tracker 5 con un Mac).

### 🎯 Dwell Control / Permanencia
Si no tienes Eye Tracking del sistema, activa **«Selección por permanencia»** en los ajustes de Háblame. Cualquier puntero (ratón, trackpad, dedo deslizado) que se quede sobre un botón el tiempo configurado lo activará. Verás una barra amarilla llenándose como retroalimentación visual.

### 🔘 Switch Control / Acceso por interruptor
1. Activa el **«Modo escaneo»** en los ajustes de Háblame.
2. Los botones se irán resaltando uno por uno automáticamente.
3. Presiona **cualquier tecla** (o conecta un switch Bluetooth que envíe una pulsación) para seleccionar el botón resaltado.

Para usar el **Switch Control nativo de iPadOS** (más completo):
- **Ajustes → Accesibilidad → Switch Control**.
- Configura tu interruptor físico o usa la pantalla / cabeza como switch.
- Activa Switch Control y Háblame funcionará con él porque todos los botones son nativos HTML.

### ⌨️ Atajos de teclado
- **Espacio** — Leer la frase actual
- **Retroceso** — Borrar última palabra
- **Esc** — Limpiar toda la frase
- **Tab** — Mover el foco entre botones
- **Enter** — Activar el botón con foco

---

## 🎨 Personalizar el vocabulario

Para que un niño se exprese mejor, **el vocabulario debe ser personal**: sus juguetes favoritos, mascotas, comidas que le gustan, nombres de familiares reales, etc.

### Forma fácil (recomendada para padres)
Abre `index.html` con un editor de texto (incluso TextEdit / Bloc de notas funciona). Busca la sección:

```js
const DEFAULT_VOCAB = {
  quiero: {
    label: 'Quiero', icon: '🙋', color: 'cat-quiero',
    items: [
      { lbl: 'agua', ico: '💧' },
      ...
```

Modifica las palabras, añade nuevas líneas siguiendo el mismo formato, y guarda. Recarga la app en el iPad.

### Para más palabras
Sigue el mismo patrón. Cada categoría tiene:
- `label`: el nombre que se muestra
- `icon`: el ícono de la categoría (emoji o cualquier carácter)
- `color`: la clase de color (ver `cat-*` en el CSS)
- `items`: la lista de palabras, cada una con `lbl` (texto) e `ico` (ícono)

> 💡 Próximamente: editor visual de vocabulario dentro de la app (ver Roadmap).

### Símbolos profesionales
Por defecto la app usa **emojis** (universales, gratuitos, ya están en el iPad). Para uso clínico podrías querer **símbolos pictográficos profesionales** como:
- **ARASAAC** — biblioteca pictográfica gratuita en español, licencia CC. https://arasaac.org
- **OpenSymbols** — usado por Cboard. https://www.opensymbols.org/
- **Mulberry Symbols** — CC-BY-SA. http://straight-street.com/

Para usarlos, descarga las imágenes y reemplaza el emoji por `<img src="symbols/agua.png">` en el código.

---

## 🛡️ Privacidad

- ✅ **No envía datos a ningún servidor.** Toda la información permanece en el iPad.
- ✅ **No usa cookies, ni análisis, ni rastreadores.** Cero.
- ✅ **No requiere registro ni cuenta.**
- ✅ El único uso opcional de internet es la **carga inicial de la fuente Atkinson Hyperlegible** desde Google Fonts. Si quieres eliminarlo, descarga la fuente al repositorio y reemplaza el `@import` por una declaración local.
- ✅ El service worker permite **operación 100 % offline** una vez cargada la primera vez.
- ⚠️ El **Web Speech API** (la voz que lee) en Safari iOS usa las voces del sistema operativo. No envía nada al servidor.

---

## 🔬 Comparación con otras apps AAC

| App | Precio | Plataforma | Offline | Open-source | Voz español |
|---|---|---|---|---|---|
| **Proloquo2Go** | ~250 USD | iPad nativa | ✅ | ❌ | ✅ |
| **TD Snap** | Gratis (con dispositivo) o 250 USD | iPad/Windows | ✅ | ❌ | ✅ |
| **Grid for iPad** | ~160 USD | iPad nativa | ✅ | ❌ | ✅ |
| **Tobii Dynavox TD Pilot** | Hardware ~12 000 USD | Hardware dedicado | ✅ | ❌ | ✅ |
| **Cboard** | Gratis | Web / PWA | ✅ | ✅ (MIT) | ✅ |
| **AsTeRICS Grid** | Gratis | Web / PWA | ✅ | ✅ | ✅ |
| **Háblame (esta app)** | Gratis | Web / PWA | ✅ | ✅ (MIT) | ✅ |

### ¿Qué hace mejor cada una?

- **Tobii Dynavox TD Pilot** es el **estándar de oro para Eye Tracking** — incluye hardware especializado de seguimiento ocular. Caro, pero clínicamente probado. Si tu hijo necesita comunicación robusta con la mirada y hay presupuesto/cobertura del seguro, considéralo en serio con un evaluador AAC profesional.
- **Proloquo2Go** tiene el vocabulario más rico, símbolos profesionales (SymbolStix) y excelente investigación pedagógica detrás.
- **TD Snap** y **Grid** son extremadamente personalizables.
- **Cboard** y **AsTeRICS Grid** son open-source y maduros — vale la pena estudiarlos como referencia o usarlos directamente si tu hijo necesita más funciones que las que Háblame ofrece hoy.

### Cuándo necesitas evaluación profesional
**Si la comunicación es central para la vida diaria del niño**, busca un **fonoaudiólogo / logopeda especializado en CAA**. Pueden:
- Evaluar el nivel de lenguaje y cognición.
- Recomendar el sistema simbólico adecuado.
- Configurar el vocabulario con vocabulario nuclear (core vocabulary) en español.
- Entrenar a la familia y a la escuela.

Háblame es un excelente punto de partida y para uso diario, pero **no reemplaza la evaluación profesional** para casos complejos.

---

## 🏗️ Arquitectura técnica

- **Frontend**: HTML5 + CSS3 + JavaScript vanilla. Sin frameworks, sin build step. Un archivo `index.html`.
- **PWA**: manifest + service worker para instalación e uso offline.
- **TTS**: Web Speech API (`SpeechSynthesis`). Usa voces del sistema operativo.
- **Almacenamiento**: `localStorage` (sólo en el dispositivo). Cero red.
- **Tipografía**: Atkinson Hyperlegible (diseñada por el Braille Institute para legibilidad accesible).
- **Paleta**: basada en la **Clave Fitzgerald**, estándar en AAC desde los años 60 para codificar partes del discurso por color.
- **Tamaño**: ~30 KB sin imágenes. Carga instantánea, funciona en cualquier iPad desde iOS 13+.

---

## 🗺️ Roadmap

- [x] Vocabulario por defecto en español
- [x] Constructor de frases con TTS
- [x] Eye Tracking compatible (a nivel SO)
- [x] Dwell control en-app
- [x] Modo escaneo (switch access)
- [x] Alto contraste
- [x] Persistencia local
- [x] PWA instalable
- [x] Funcionamiento offline
- [ ] Editor visual de vocabulario dentro de la app
- [ ] Importar/exportar tableros como JSON
- [ ] Soporte para imágenes personalizadas (foto de mamá, mascota, etc.)
- [ ] Predicción de palabras
- [ ] Historial de frases frecuentes
- [ ] Integración con biblioteca ARASAAC
- [ ] Variantes regionales (es-MX, es-AR, es-ES, es-CO…)
- [ ] Versión nativa SwiftUI con Eye Tracking del SO integrado más profundamente

---

## 🤝 Contribuir

Pull requests bienvenidos. Si tienes a un niño que usa la app y faltan palabras importantes, abre un issue describiendo qué le ayudaría.

---

## 📜 Licencia

MIT — usa, modifica y distribuye libremente, incluso para uso comercial. La única condición es mantener el aviso de copyright.

---

## 🙏 Agradecimientos e inspiración

- **Cboard** (https://github.com/cboard-org/cboard) — proyecto AAC open-source de referencia, financiado por UNICEF.
- **AsTeRICS Grid** (https://github.com/asterics/AsTeRICS-Grid) — sistema modular AAC open-source.
- **ARASAAC** — biblioteca de símbolos en español, gobierno de Aragón.
- **Atkinson Hyperlegible** — Braille Institute.
- La comunidad de **fonoaudiólogos especializados en CAA** que comparten vocabulario nuclear en español.
