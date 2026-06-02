# ♿ Accesibilidad iPadOS · Eye Tracking, Dwell Control, Switch Control

Háblame está diseñado para funcionar con las funciones de accesibilidad nativas de iPadOS. Como los botones son grandes, semánticos (HTML estándar) y tienen etiquetas correctas, **el sistema operativo hace casi todo el trabajo**.

---

## 👁️ Eye Tracking (Seguimiento ocular) — iPadOS 18+

### Compatibilidad
Eye Tracking nativo requiere:
- **iPadOS 18 o superior**
- **iPad Pro** con chip M2 o posterior, o **iPad Air** con chip M2 o posterior. Comprueba la página oficial de Apple para el listado actualizado.

### Activación
1. **Ajustes → Accesibilidad → Eye Tracking** (Seguimiento ocular).
2. Activa el interruptor.
3. Sigue el proceso de **calibración**: aparecen puntos en la pantalla y debes mirarlos uno a uno. Toma ~30 segundos.
4. Configura **«Permanencia automática» (Auto-Dwell)**: tiempo que la mirada debe quedarse fija para activar un toque. Empieza con **1.2–1.5 segundos** y ajusta.
5. Activa **«Indicador de Permanencia»** para que el niño vea un círculo llenándose cuando enfoca un botón.

### Uso con Háblame
1. Abre Háblame desde la pantalla de inicio.
2. Mantén el iPad a **40–60 cm de distancia**, idealmente sobre un soporte estable (un atril o brazo articulado funciona mejor que la mano).
3. **No actives** el dwell control interno de Háblame (déjalo apagado en Ajustes). El sistema operativo manejará la selección por mirada.
4. El niño mira un botón. Tras el tiempo configurado, iPadOS dispara un «toque» automático y el botón se activa.

### Consejos
- Buena iluminación en la cara del niño, pero **evita luz directa contra la cámara**.
- Recalibra si el niño cambia de posición o si el iPad se mueve.
- Para sesiones largas, da descansos visuales cada 15–20 minutos.

---

## 🎯 Dwell Control sin Eye Tracking del SO

Si tu iPad **no soporta Eye Tracking nativo** o quieres usar otro sistema:

### Opción A · Dwell interno de Háblame
1. Abre los ajustes de Háblame (⚙️) y activa **«Selección por permanencia»**.
2. Ajusta el tiempo de permanencia.
3. Conecta cualquier dispositivo apuntador:
   - Trackpad o ratón Bluetooth (Magic Mouse, etc.)
   - Cualquier dispositivo HID estándar
4. Cuando el cursor se quede sobre un botón el tiempo configurado, se activará. Verás una barra amarilla llenándose como retroalimentación visual.

### Opción B · AssistiveTouch del sistema con Dwell
iPadOS también ofrece Dwell de sistema completo (no requiere Eye Tracking):
1. **Ajustes → Accesibilidad → Control por puntero → Dwell Control**.
2. Activa y configura el tiempo.
3. Funcionará sobre cualquier app, incluida Háblame.

---

## 🔘 Switch Control (Acceso por interruptor)

Para niños que usan un **switch físico** (botón grande, soplido, parpadeo, etc.).

### Opción A · Switch Control nativo de iPadOS (recomendado)
1. **Ajustes → Accesibilidad → Switch Control**.
2. **«Interruptores → Agregar interruptor nuevo»**:
   - **Externo**: si tu switch se conecta por Bluetooth (modelos compatibles: AbleNet, RJ Cooper, etc.), conéctalo y se detectará.
   - **Pantalla**: usa la pantalla entera como switch.
   - **Cámara**: gira la cabeza a izquierda/derecha como switch.
3. Configura el **estilo de escaneo** (automático, manual, paso-a-paso por elemento).
4. Activa Switch Control con el atajo de accesibilidad (triple-clic en el botón de inicio o Home).

Como Háblame usa **botones HTML estándar con `aria-label`**, Switch Control los reconoce automáticamente.

### Opción B · Modo escaneo interno de Háblame
Más sencillo si sólo quieres usarlo dentro de la app:
1. Abre Ajustes de Háblame (⚙️) → activa **«Modo escaneo»**.
2. Ajusta la velocidad de escaneo.
3. Los botones se irán resaltando uno por uno.
4. **Cualquier tecla del teclado** activa el botón resaltado (algunos switches Bluetooth se programan para enviar pulsaciones de teclado).

---

## 🗣️ VoiceOver (TalkBack para iOS)

Háblame es compatible con VoiceOver porque usa elementos semánticos y `aria-label`. Esto es útil para:
- Niños con **discapacidad visual además de no verbalismo**.
- Pruebas de accesibilidad.

---

## 📐 Recomendaciones de configuración inicial

Para un niño de **9 años, cognición típica, no verbal**:

| Ajuste | Valor sugerido para empezar |
|---|---|
| Tamaño de botones | 140–160 px |
| Tiempo de permanencia | 1.2–1.5 s |
| Velocidad de voz | 0.9x |
| Alto contraste | Apagado (a menos que haya baja visión) |
| Leer al seleccionar | Encendido (retroalimentación inmediata acelera el aprendizaje) |

Ajusta según vayas observando:
- Si el niño activa botones sin querer → **aumenta** el tiempo de permanencia.
- Si se frustra esperando → **disminuye** el tiempo de permanencia.
- Si no acierta al botón → **aumenta** el tamaño.

---

## 🚨 Aviso importante

Estas herramientas son **complementarias, no sustitutivas** de una evaluación profesional de CAA. Si tu hijo va a depender de un sistema AAC para comunicarse a diario, busca un **fonoaudiólogo / logopeda especializado en CAA** que pueda:

- Hacer una evaluación del lenguaje receptivo y expresivo.
- Recomendar **vocabulario nuclear** (palabras de alta frecuencia como «yo», «quiero», «más», «no», «aquí»…) que es la base de la comunicación efectiva en cualquier sistema AAC serio.
- Entrenar al niño, la familia y la escuela.

Háblame es un buen **punto de partida** y un excelente complemento para uso casual, pero el sistema AAC «correcto» depende del perfil específico del niño.
