# Plan del tablero Kanban — Registro de Usuarios

## Objetivo del sprint
Entregar en dos semanas (10 días de trabajo) un módulo de Registro de Usuarios que permita completar un formulario, validar los datos y guardar la cuenta correctamente.

## Columnas del tablero
| Columna | Para qué se usa | Cuándo mover una tarjeta |
|---|---|---|
| Backlog | Ideas y tareas registradas que todavía no se van a trabajar. | Cuando el equipo la prioriza, pasa a Por hacer. |
| Por hacer | Tareas seleccionadas para este sprint. | Cuando un desarrollador empieza a trabajar. |
| En progreso | Tareas que se están desarrollando. | Cuando el trabajo está listo para revisión. |
| En revisión | Tareas que esperan comprobación de otro integrante. | Cuando cumple los criterios, pasa a Terminado; si falla, vuelve a En progreso. |
| Terminado | Trabajo revisado y que cumple sus criterios de aceptación. | No mover aquí sin probarlo. |

## Historias de usuario y criterios de aceptación

### HU-01: Crear el formulario de registro
**Historia:** Como usuario, quiero ingresar mis datos personales para crear una cuenta.

**Criterios de aceptación**
- El formulario muestra los campos nombre, correo y contraseña.
- No permite enviar el formulario si falta un dato obligatorio.
- Al completar correctamente el registro, muestra un mensaje de confirmación.
- Los campos y botones se pueden utilizar desde computadora y celular.

**Responsable:** Desarrollador 1 — pantalla y formulario.

### HU-02: Guardar la información del usuario
**Historia:** Como usuario, quiero que mis datos se guarden para poder utilizar mi cuenta posteriormente.

**Criterios de aceptación**
- Los datos válidos se guardan correctamente.
- No se permite registrar dos cuentas con el mismo correo.
- La contraseña se guarda usando el mecanismo de protección definido para el proyecto.
- Si ocurre un error al guardar, se informa al usuario sin mostrar datos sensibles.

**Responsable:** Desarrollador 2 — almacenamiento y seguridad.

### HU-03: Validar los datos ingresados
**Historia:** Como usuario, quiero que el sistema revise mis datos para evitar errores durante el registro.

**Criterios de aceptación**
- El sistema comprueba que el correo tenga un formato válido.
- El sistema comprueba que la contraseña cumpla los requisitos definidos.
- Si un dato no es correcto, indica qué debe corregirse.
- Los datos incorrectos no se guardan.

**Responsable:** Desarrollador 3 — validaciones y mensajes.

## Distribución del trabajo entre cuatro desarrolladores
| Integrante | Responsabilidad principal | Trabajo durante las dos semanas |
|---|---|---|
| Desarrollador 1 | Interfaz | Diseñar el formulario, organizar los campos y comprobar la vista en computadora y celular. |
| Desarrollador 2 | Datos y seguridad | Preparar el almacenamiento, guardar usuarios, evitar correos repetidos y proteger contraseñas. |
| Desarrollador 3 | Validaciones | Revisar campos obligatorios, formato del correo, requisitos de contraseña y mensajes de error. |
| Desarrollador 4 | Integración y pruebas | Unir las partes, revisar el funcionamiento completo, probar casos correctos e incorrectos y preparar la entrega. |

> Los nombres de usuario de GitHub de los cuatro integrantes deben colocarse en el campo Assignees de cada tarea. Por ahora, las responsabilidades están distribuidas por rol porque no se han indicado los cuatro usuarios de GitHub.

## Calendario de dos semanas
| Día | Actividad principal | Responsable |
|---|---|---|
| 1–2 | Diseñar y crear el formulario | Desarrollador 1 |
| 3–4 | Preparar el almacenamiento y guardar usuarios | Desarrollador 2 |
| 5–6 | Validar datos y mostrar mensajes | Desarrollador 3 |
| 7–8 | Integrar las partes y corregir incompatibilidades | Desarrollador 4 con apoyo del equipo |
| 9 | Probar el registro con datos correctos e incorrectos | Desarrollador 4 y equipo |
| 10 | Corregir detalles y preparar la entrega | Todo el equipo |

## Cómo se dará seguimiento
- Cada tarjeta debe tener una persona responsable y una fecha de entrega.
- Cada integrante actualizará el estado de su tarea cuando avance.
- En la reunión diaria, el equipo comentará qué terminó, qué hará después y si tiene algún problema.
- Si una tarea se bloquea, se deja un comentario en la tarjeta explicando el problema y quién ayudará a resolverlo.
- Una tarjeta solo pasa a Terminado cuando cumple todos sus criterios y alguien del equipo la revisó.

## ¿Por qué este tablero ayuda al equipo?
Con las columnas se puede ver rápidamente qué falta, qué se está haciendo y qué ya fue revisado. Al asignar una persona a cada tarea, todos saben quién debe avanzar cada parte y a quién consultar si aparece un problema. Los criterios de aceptación también ayudan a comprobar que el módulo funciona antes de darlo por terminado, y las actualizaciones permiten seguir el avance durante las dos semanas sin depender de preguntar a cada integrante.
