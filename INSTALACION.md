# Cómo instalar el Asistente Docente Nicaragua

Guía paso a paso para docentes. Toma unos 5 minutos y solo se hace una vez. **Es gratis.**

Puedes instalarla en **Claude** o en **Gemini** (con cuenta personal). Elige una.

## Paso 0 — Descarga el archivo

1. Entra a la sección **Releases** de este repositorio (columna derecha de la página principal).
2. En **Assets**, descarga **`asistente-docente-nicaragua.zip`**.

## Opción A — Claude (claude.ai)

1. Entra a **claude.ai** y crea una cuenta gratuita (o inicia sesión).
2. Ve a **Configuración → Capacidades** y activa **la ejecución de código y la creación de archivos**. Sin esto la Skill no funciona.
3. En **Configuración → Capacidades → Skills**, sube el archivo **`asistente-docente-nicaragua.zip`**. **No lo descomprimas.**
4. Comprueba que "asistente-docente-nicaragua" aparece en la lista y está activada.

## Opción B — Gemini (cuenta personal de Gmail)

1. Entra a **gemini.google.com** con tu **Gmail personal**. Las cuentas de colegio o de trabajo (Google Workspace) pueden no tener esta función.
2. **Descomprime** el zip: obtendrás una carpeta llamada `asistente-docente-nicaragua`.
3. Ve a **Personalizar → Habilidades → Crear** y sube la **carpeta completa** (con su subcarpeta `references`).
4. Comprueba que "asistente-docente-nicaragua" aparece en tus Habilidades.

> Los nombres de los menús pueden cambiar con el tiempo. Si no encuentras "Habilidades", busca la opción de personalizar o de agregar habilidades de tu cuenta.

## Úsala

Abre un **chat nuevo** y sigue este orden:

| Paso | Escribe | Qué pasa |
|---|---|---|
| 1 | `!programacion` y adjunta o pega tu Programación Didáctica | Resume tu Programación y te pide confirmar colegio, docente, asignatura y grado |
| 2 | `!plan` | Te pide los datos de la clase en un solo mensaje y te muestra el Plan con inicio, desarrollo y cierre |
| 3 | `!evaluacion` | Diseña el instrumento del indicador según la política de tu colegio y la Guía del Estudiante |
| Cuando quieras | `!ajuste` y lo que quieres cambiar | Cambia solo eso y te muestra de nuevo el resultado |

**Consejos**
- Usa **un chat nuevo por documento** (un Plan, un instrumento). Rinde más el límite de uso de la cuenta gratuita.
- **No escribas nombres ni datos de tus estudiantes.** No hacen falta.
- La Skill no inventa fechas ni datos de tu clase: si algo falta, te lo pregunta.
- Revisa siempre lo que genera antes de usarlo: tú decides y tú firmas.

## Si algo falla

- **No responde a los comandos (`!plan`, etc.):** revisa que la Skill esté activada y abre un chat nuevo.
- **Gemini no sigue el flujo o no lee las plantillas:** confirma que subiste la **carpeta completa** con `references`, no solo `SKILL.md`.
- **No se descarga el Word de la Guía (Claude):** el navegador puede bloquear la descarga. Busca el ícono a la derecha de la barra de direcciones y elige **Permitir siempre** para claude.ai. Si no baja, escríbele a la Skill "no pude descargar la Guía" y te da el texto para copiar a Word.
- **Aviso de límite de uso:** espera el tiempo que indica.
- **Ya tenías una versión anterior instalada:** elimínala antes de subir esta.

¿Dudas o sugerencias? Abre un *Issue* en este repositorio.
