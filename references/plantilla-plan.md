# Plantilla — Plan Diario de Clases

Muestra la vista previa en el chat con **esta estructura exacta**, sin envolverla en bloques de código. Reemplaza cada `{{campo}}` con datos reales (de la Ficha del docente, de la Programación o confirmados por el docente, ver 1.6). Los textos entre corchetes son instrucciones, no contenido.

| Versión | Fecha | Autor | Descripción del Cambio |
| :--- | :--- | :--- | :--- |
| v1.0.0 | [fecha en que se genera el plan] | {{nombre_docente}} (cocreado con Asistente IA) | Generación inicial del plan diario. |
| [vNext, solo si hubo `!ajuste`] | [fecha del ajuste] | {{nombre_docente}} (cocreado con Asistente IA) | [Ajuste realizado en la sesión] |

La tabla de versiones sirve solo para seguir los ajustes de la conversación.

# 🏫 {{nombre_colegio}}
## PLAN DIARIO DE CLASES No. {{numero_plan}}

### 📋 DATOS GENERALES
| CAMPO | DETALLE | CAMPO | DETALLE |
| :--- | :--- | :--- | :--- |
| **DOCENTE:** | {{nombre_docente}} | **FECHA:** | {{fecha}} |
| **ÁREA / ASIGNATURA:** | {{asignatura}} | **GRADO:** | {{grado}} |
| **UNIDAD:** | {{numero_y_nombre_unidad}} | **SECCIÓN:** | {{seccion}} |
| **MÉTODO:** | {{metodo_didactico}} | **HORARIO Y DURACIÓN:** | {{horario_y_duracion}} |

**ESTRATEGIAS:**
- **Cognitiva:** {{estrategia_cognitiva_detalle}}
- **Metacognitiva:** {{estrategia_metacognitiva_detalle}}

### 📘 I. ASPECTOS CURRICULARES
(Todo se transcribe literal de la Programación.)
- **Competencia del eje transversal:** {{comp_eje}}
- **Competencia de grado:** {{competencia_grado}}
- **Indicador de logro:** {{indicador_logro}}
- **Contenido(s):** {{contenidos}}
- **Criterios de evaluación:** {{criterios_evaluacion_listado}}

### 📝 II. SECUENCIA DIDÁCTICA
| MOMENTO | ACTIVIDADES DE APRENDIZAJE | EVALUACIÓN FORMATIVA |
| :--- | :--- | :--- |
| **INICIO** ({{minutos}} min) — Motivación, saberes previos y propósito | {{pregunta_detonadora_propuesta_activacion_conocimientos_previos_y_presentacion_del_indicador_en_lenguaje_del_estudiante}} | {{evidencia_formativa_inicio}} |
| **DESARROLLO** ({{minutos}} min) — Construcción y práctica | {{mediacion_del_contenido_ejemplos_ejercicios_y_actividades_en_orden_de_complejidad}} | {{evidencia_formativa_desarrollo}} |
| **CIERRE** ({{minutos}} min) — Síntesis y metacognición | {{sintesis_revision_colectiva_y_actividad_metacognitiva}} | {{evidencia_formativa_cierre}} |

La suma de minutos de los tres momentos debe coincidir con la duración que dio el docente.

### 📌 ORIENTACIÓN DE TAREA
- **Tarea o Producto asignado (propuesta):** {{instrucciones_tarea_producto_evaluable}}
- **Evaluación formativa:** {{como_se_retroalimenta_a_partir_de_los_criterios}}

### 🛠️ RECURSOS Y OBSERVACIONES
| RECURSOS UTILIZADOS | OBSERVACIONES |
| :--- | :--- |
| {{lista_recursos_utilizados}} | {{notas_del_docente_o_Sin_observaciones}} |

| Firma del docente | Firma del coordinador pedagógico / director |
| :--- | :--- |
| __________________________ | __________________________ |

## Reglas de codificación
- Sin LaTeX ni HTML; sin envolver la vista previa en ```.
- Si el docente escribe `|` o saltos de línea manuales, reemplázalos por comas o guiones para no romper las tablas.
- **No menciones ningún instrumento de evaluación** (rúbrica, lista de cotejo, escala, guía de observación) ni su tipo, en ninguna parte del Plan. La evaluación formativa describe cómo se observa y retroalimenta (participación, revisión del producto, preguntas orales) a partir de los criterios.
- Marca como "(propuesta)" la pregunta detonadora, la dinámica, la tarea y la distribución de tiempos que decidiste tú, para que el docente sepa qué puede cambiar con `!ajuste`.
- Recursos: lista solo los que se desprenden de las actividades (pizarra, cuaderno, libro de texto, material impreso); no inventes recursos que el centro podría no tener (proyector, internet) salvo que el docente los mencione.
