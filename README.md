# 🏷️ Banner Racha · Técnicas de Almacén

Banner interactivo gamificado diseñado para el aula virtual del módulo **Técnicas de Almacén** (FP Comercio y Marketing).

## 🚀 Pruébalo ahora

**[→ Testearlo en directo](https://albertosanchezedu.github.io/banner-racha-tecnicas-almacen/banner_almacen.html)**

---

## ¿Qué hace?

Cada día aparece una pregunta diferente sobre el módulo — datos curiosos, situaciones reales, conceptos clave — que el alumno responde en segundos directamente desde la portada del curso.

El aprendizaje se gamifica a través de un sistema completo de **rachas, XP, ligas y mini-juegos**: cada respuesta correcta suma puntos y mantiene la racha viva. Los alumnos que mantengan la racha más alta y alcancen las ligas superiores pueden optar a **puntos extra** en el módulo formativo.

![github-small](https://github.com/albertosanchezedu/banner-racha-tecnicas-almacen/blob/13444b6aa9ec9b1273bf35f25243bfdaa8a6953f/images/Captura%20de%20pantalla%202026-03-16%20a%20las%2017.51.56%402x.png)
---

## 🎮 Sistema de juego

### Preguntas diarias
- **70+ preguntas** rotativas sobre logística, almacenaje, seguridad, gestión de stocks, transporte y más
- La pregunta del día cambia cada día con **opciones aleatorizadas** — sin patrón fijo en las respuestas
- Formatos variados: **test de opción múltiple** y **ordenar procesos** (tap-to-place)
- Dato curioso revelado al responder
- Botón "Siguiente →" para seguir practicando con preguntas extra

### ⚡ Sistema de rachas
- Cada respuesta correcta **suma 1 a la racha**
- Un fallo **reinicia la racha a 0**
- Se guarda el **récord personal** de racha más alta
- Mensajes motivacionales que cambian según la racha alcanzada

### 🛡️ Protectores de racha
- Al llegar a **10, 20, 30...** aciertos consecutivos se gana un **escudo protector**
- El escudo **absorbe un fallo** sin romper la racha
- Se pueden acumular varios escudos
- Los escudos también se pueden ganar en el mini-juego bonus

### 🏆 Sistema de XP y ligas
Cada acción tiene su recompensa o penalización:

| Acción | XP |
|--------|-----|
| Respuesta correcta | +20 XP |
| Racha de 5+ aciertos | ×1.5 multiplicador |
| Racha de 10+ aciertos | ×2 multiplicador |
| Respuesta incorrecta | -10 XP |

Las ligas por las que pueden progresar los alumnos:

![github-small](https://github.com/albertosanchezedu/banner-racha-tecnicas-almacen/blob/13444b6aa9ec9b1273bf35f25243bfdaa8a6953f/images/Captura%20de%20pantalla%202026-03-16%20a%20las%2017.53.39.png)

| Liga | XP necesario |
|------|-------------|
| 📦 Aprendiz de almacén | 0 XP |
| 🏷️ Operario | 200 XP |
| 🔍 Picker | 500 XP |
| 📋 Responsable de turno | 1.000 XP |
| 🚛 Jefe de almacén | 2.000 XP |
| 🏭 Director logístico | 4.000 XP |

El badge de nivel en la esquina superior derecha muestra la liga actual, una barra de progreso al siguiente nivel y el XP total. Al hacer clic se despliega un panel con el detalle completo.

### ⚡ Mini-juego bonus

![github-small](https://github.com/albertosanchezedu/banner-racha-tecnicas-almacen/blob/13444b6aa9ec9b1273bf35f25243bfdaa8a6953f/images/Captura%20de%20pantalla%202026-03-16%20a%20las%2017.53.16.png)

- Se activa de forma **aleatoria cada ~7 preguntas** (60% de probabilidad)
- Pantalla de aviso antes de empezar: "¡Bonus desbloqueado!"
- **4 segundos** para tocar el mayor número de emojis posible
- Recompensas según emojis cazados:

| Emojis | Premio |
|--------|--------|
| 1–3 | +20 XP |
| 4–6 | +50 XP |
| 7–9 | +80 XP |
| 10–12 | +120 XP |
| 13+ | +120 XP + 🛡️ protector |

![github-small](https://github.com/albertosanchezedu/banner-racha-tecnicas-almacen/blob/13444b6aa9ec9b1273bf35f25243bfdaa8a6953f/images/Captura%20de%20pantalla%202026-03-16%20a%20las%2017.53.20.png)

---

## 🔒 Protección anti-copia

El banner incluye medidas para dificultar que el alumnado copie las preguntas a herramientas de IA:
- Selección de texto desactivada
- Menú contextual (clic derecho) bloqueado
- Atajos de teclado de copia bloqueados (Ctrl+C, Ctrl+A, Ctrl+X, Ctrl+U)

---

## 💾 Guardado de progreso

El progreso (racha, récord, XP, liga, escudos) se guarda en el **localStorage del navegador** de cada alumno. Persiste entre sesiones siempre que el alumno use el mismo navegador y dispositivo. No se borra con recargas normales — solo si el alumno limpia manualmente los datos del navegador o usa modo incógnito.

---

## 📐 Uso en EducaMadrid / Moodle

Incrustar en la descripción de sección:

```html
<p><iframe style="border-radius: 14px; display: block;"
    src="https://albertosanchezedu.github.io/banner-racha-tecnicas-almacen/banner_almacen.html"
    width="100%" height="420" frameborder="0" scrolling="no">
  </iframe></p>
```

---

*Creado por Alberto Sánchez Cabanillas — Docente FP Comercio y Marketing · [LinkedIn](https://www.linkedin.com/in/albertosanchezcabanillas/) · Curso 2025-2026*
