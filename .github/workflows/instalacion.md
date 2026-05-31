# 📲 Guía de instalación paso a paso

Esta guía está pensada para **padres y madres sin conocimientos técnicos**. Si te trabas, escríbenos un issue en GitHub.

---

## Método 1 · Más fácil: usar la versión ya publicada

1. En el iPad, abre **Safari** (no Chrome — Safari maneja mejor el modo PWA y la voz en español).
2. Escribe la dirección que te haya dado quien te compartió la app, por ejemplo:
   ```
   https://<usuario>.github.io/hablame-aac/
   ```
3. Cuando cargue, toca el ícono **«Compartir»** (cuadrado con flecha hacia arriba, arriba a la derecha en Safari).
4. Desliza la lista de opciones hasta encontrar **«Agregar a pantalla de inicio»**. Tócalo.
5. Aparecerá una vista previa. Puedes editar el nombre si quieres. Toca **«Agregar»** (arriba a la derecha).
6. Cierra Safari. Verás un ícono nuevo de «Háblame» en la pantalla principal.
7. Tócalo. La app abrirá **a pantalla completa**, sin barras del navegador, como si fuera una app nativa.

✅ Listo. La app funcionará sin internet a partir de la segunda apertura.

---

## Método 2 · Hospedar tu propia copia en GitHub (gratis)

Si quieres tu propia versión que puedas modificar:

### Paso 1 · Crear cuenta de GitHub
1. Ve a [github.com](https://github.com) y registra una cuenta gratuita.

### Paso 2 · Crear el repositorio
1. Descarga este repositorio como ZIP desde GitHub (botón verde «Code → Download ZIP»).
2. Descomprime el ZIP en tu computadora.
3. En GitHub, crea un repositorio nuevo. Llámalo, por ejemplo, `hablame-aac`. Hazlo **público** (necesario para GitHub Pages gratis).
4. Sube todos los archivos del ZIP al repositorio (arrastrar y soltar funciona en la interfaz web de GitHub).

### Paso 3 · Activar GitHub Pages
1. En tu repositorio, ve a la pestaña **«Settings»**.
2. En el menú lateral, busca **«Pages»**.
3. En «Source» elige **«GitHub Actions»** (el workflow `.github/workflows/deploy.yml` ya está incluido y desplegará automáticamente).
4. Espera 1-2 minutos.
5. Te aparecerá una URL como `https://<tu-usuario>.github.io/hablame-aac/`.

### Paso 4 · Instalar en el iPad
Sigue los pasos del **Método 1** usando tu nueva URL.

---

## Método 3 · Uso local sin internet (sin GitHub)

Si sólo quieres probarlo sin publicar nada:
1. Descarga los archivos a una memoria USB o envía `index.html` al iPad por AirDrop / correo.
2. Abre `index.html` desde Archivos / iCloud / lo que uses.
3. Algunas funciones (como service worker / offline persistente) requieren HTTPS y no funcionarán abriendo el archivo directamente, **pero la voz, los botones y el guardado local sí funcionarán**.

---

## Solución de problemas

### «No suena la voz»
- Asegúrate de que el iPad **no esté en silencio** (interruptor lateral o Centro de Control).
- Ve a **Ajustes → Accesibilidad → Contenido leído → Voces → Español** y descarga una voz de calidad mejorada (las premium son mucho mejores).
- En el modal de Ajustes de Háblame, elige una voz de la lista.

### «Sólo tengo una voz en español y suena rara»
- En **Ajustes del iPad → Accesibilidad → Contenido leído → Voces → Español**, baja la voz **«Mónica (Mejorada)»** o **«Paulina (Mejorada)»**. Son mucho más naturales.

### «El ícono no aparece después de Agregar a pantalla de inicio»
- Asegúrate de hacerlo desde **Safari**, no desde Chrome o Firefox.

### «La app se ve pequeña / con barras del navegador»
- Tienes que abrirla desde el **ícono de la pantalla de inicio**, no desde Safari directamente.

### «No persisten las configuraciones»
- Asegúrate de no estar en **modo privado** de Safari.

---

## ¿Y Eye Tracking del iPad?

Ver [accesibilidad-ipados.md](accesibilidad-ipados.md).
