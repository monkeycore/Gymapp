# Entrena

Registro de entrenamientos de fuerza pensado para el móvil: llevas la sesión serie a serie, con temporizador de descanso, y ves tu progreso por semanas.

**Demo:** https://monkeycore.github.io/Gymapp/

## Qué hace

- **Rutina en dos días** (Día A / Día B), con editor propio para añadir, editar, reordenar y eliminar ejercicios.
- **Sesión guiada** serie a serie: registras cada serie y la app avanza al siguiente ejercicio.
- **Temporizador de descanso** con presets de 30, 60 y 90 segundos, cuenta atrás visual en arco y aviso sonoro al terminar. Se puede saltar.
- **Historial** con gráfico de las últimas 13 semanas.
- Confirmación al abandonar una sesión a medias, para no perder lo registrado por error.

## Uso

Es un único `index.html` sin dependencias ni build. En iOS puedes añadirlo a la pantalla de inicio y se abre a pantalla completa, como una app.

Los datos se guardan en el `localStorage` del navegador: no hay cuentas ni servidor, pero tampoco sincronización entre dispositivos. Si borras los datos del navegador, se pierde el historial.
