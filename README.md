# Asistente Docente Nicaragua

Skill gratuita para docentes de Primaria y Secundaria de Nicaragua. Ayuda a:

- **Analizar** la Programación Didáctica (`!programacion`).
- **Preparar el Plan de Clase** con inicio, desarrollo y cierre; el encabezado se toma de la Programación (`!plan`).
- **Diseñar instrumentos de evaluación** según el MINED: rúbrica, rúbrica analítica, guía de observación, escala de valoración, lista de cotejo (`!evaluacion`). Funciona con la política de tu colegio: **un instrumento por indicador con los 3 criterios**, o **un instrumento por cada criterio**.
- **Redactar el instructivo para los estudiantes** (Guía del Estudiante), con el instrumento incluido.
- **Ajustar** cualquier documento (`!ajuste`).

No envía nada a ningún sistema ni pide correos: todo queda en tu conversación.

## Cómo instalarla

Descarga este repositorio desde GitHub: botón verde **Code → Download ZIP** (o el `.zip` de la sección *Releases*, si existe).

**Gemini (cuenta personal de Gmail):** Personalizar → Habilidades → Crear → sube la carpeta completa `asistente-docente-nicaragua` (con su subcarpeta `references`).

**Claude (claude.ai):** Configuración → Capacidades → Skills → Subir skill → sube el `.zip` que contiene la carpeta `asistente-docente-nicaragua`.

## Cómo usarla

1. Adjunta o pega tu Programación Didáctica y escribe `!programacion`. La Skill lee de ahí el colegio, tu nombre, la asignatura y el grado, y solo te pide confirmarlos.
2. Escribe `!plan` para cada clase y `!evaluacion` para los instrumentos de cada indicador. La primera vez te preguntará cuál es la política de tu colegio.
3. Si algo no te gusta, escribe `!ajuste` y di qué quieres cambiar.

**Consejo:** usa una conversación nueva por documento (un Plan, un instrumento); así rinde más el límite de uso de la cuenta gratuita.

## Aviso importante

Esta Skill es una ayuda de planificación hecha con inteligencia artificial. **No es un producto oficial del MINED ni de ningún colegio.** Revisa siempre lo que genera antes de usarlo en el aula: tú decides, y tú firmas.

## De dónde viene: Colegio Hogar Paulo VI y AppRubric

Esta Skill nació en el **Colegio Hogar Paulo VI**, donde se usa desde 2026 en su versión institucional, **sincronizada con AppRubric**: además del Plan y los instrumentos, entrega un archivo que el docente importa en AppRubric con un clic, sin volver a digitar nada.

**AppRubric** es un sistema de evaluación diseñado para cumplir el Instructivo de Evaluación del MINED (Capítulo V) y quitarle papeleo al docente y a la Dirección:

- **Cuaderno de Registro y notas por corte**, con las reglas del MINED aplicadas por el servidor (escala AA/AS/AF/AI, sin decimales, estructura de puntos fija por materia).
- **Instrumentos con control de calidad:** todo instrumento cubre los 3 criterios y el Director o Coordinador lo aprueba antes de que se capture una sola nota.
- **Cierre de cortes:** un corte cerrado queda congelado y solo la Dirección puede reabrirlo, con motivo registrado.
- **Excepciones del Arto. 32** y traslados de estudiantes a mitad de corte, con trazabilidad.
- **Portal de resultados** para estudiantes y familias ("Mi Progreso"), y seguimiento de Dirección y Coordinación.
- **Sincronización con Google Classroom** (en piloto).

**¿Tu colegio quiere implementar AppRubric?** Esta Skill es solo la puerta de entrada: la gestión completa de evaluación del colegio está en AppRubric. Para conversar sobre una implementación, escribe a **adavilam@gmail.com** con el asunto "Quiero implementar AppRubric", o abre un *Issue* en este repositorio con ese título.

## Autoría

Creada por **Alvaro Dávila (Adavilam)**, 2026. © Todos los derechos reservados salvo lo que permite la licencia de abajo.

## Licencia

[Creative Commons Atribución-NoComercial-SinDerivadas 4.0 Internacional (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.es).

**Puedes, sin pedir permiso:**
- Instalarla tal cual en tu cuenta personal y usarla en tu trabajo docente.
- Compartirla **sin cambios** con otros docentes, citando la autoría y enlazando este repositorio.

**Necesitas mi autorización previa y por escrito para:**
- Modificar, traducir, recortar o adaptar cualquiera de sus archivos y distribuir el resultado.
- Incluirla en otro producto, servicio o plataforma.
- Cualquier uso comercial.

Para pedir una autorización, escribe a **adavilam@gmail.com** o abre un *Issue* en este repositorio. El texto completo está en el archivo `LICENSE`.
