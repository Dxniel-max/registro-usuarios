# Registro de Usuarios

## 1. Descripción del proyecto
Este proyecto busca organizar el desarrollo de un módulo básico de registro de usuarios. El sistema permitirá ingresar datos personales, validar la información y guardar los datos para su posterior uso.

## 2. Objetivo general
Desarrollar un módulo de registro sencillo, funcional y fácil de utilizar, controlando las actividades mediante un tablero Kanban de GitHub Projects.

## 3. Alcance
- Mostrar un formulario para ingresar nombre, correo y contraseña.
- Comprobar que los campos obligatorios estén completos.
- Validar el formato del correo y los requisitos de la contraseña.
- Guardar la información del usuario.
- Informar al usuario si el registro fue exitoso o si ocurrió un error.
- Revisar y probar el funcionamiento antes de la entrega.

## 4. Historias de usuario
| Código | Historia | Criterio principal de aceptación |
|---|---|---|
| HU-01 | Como usuario, quiero ingresar mis datos personales para crear una cuenta. | El formulario solicita nombre, correo y contraseña; no acepta campos obligatorios vacíos y muestra confirmación. |
| HU-02 | Como usuario, quiero que mis datos se guarden para utilizar mi cuenta posteriormente. | La información se guarda; el correo no se repite y se informa si ocurre un error. |
| HU-03 | Como usuario, quiero que el sistema valide mis datos para evitar errores. | Se comprueba el formato del correo, la contraseña y se indica qué dato debe corregirse. |
| HU-04 | Como equipo, queremos revisar e integrar las funciones para entregar un módulo estable. | Se revisa el código, se prueban datos válidos e inválidos y se corrigen los errores encontrados. |

## 5. Organización del trabajo
El trabajo se planifica para un periodo de dos semanas. Las responsabilidades se distribuirán entre cuatro desarrolladores; los nombres de los responsables se deben registrar en las asignaciones de GitHub Projects.

| Periodo | Actividad | Resultado esperado |
|---|---|---|
| Días 1–2 | Diseño y creación del formulario (HU-01) | Formulario visible y campos definidos |
| Días 3–4 | Guardado de información (HU-02) | Datos almacenados y correo único |
| Días 5–6 | Validación de datos (HU-03) | Validaciones y mensajes de error |
| Días 7–8 | Revisión e integración | Funciones conectadas y código revisado |
| Días 9–10 | Pruebas y correcciones (HU-04) | Módulo probado y listo para presentar |

## 6. Flujo Kanban
Las tareas se moverán por las columnas del proyecto según su estado real:
1. **Reserva / Backlog:** tareas registradas que aún no se han priorizado.
2. **Por hacer:** tareas seleccionadas y listas para comenzar.
3. **En progreso:** tareas que se están desarrollando.
4. **Terminado:** tareas que cumplen sus criterios de aceptación y fueron verificadas.

> Una tarea solo debe pasar a **Terminado** cuando se haya completado y comprobado. Las columnas deben reflejar el avance real, no un avance supuesto.

## 7. Definición de terminado
Una historia se considera terminada cuando:
- Cumple todos sus criterios de aceptación.
- Se probó con datos correctos e incorrectos, según corresponda.
- No presenta errores conocidos que impidan su uso.
- El resultado fue revisado por el equipo.

## 8. Seguimiento del proyecto
El avance se controlará revisando la ubicación de cada tarjeta en GitHub Projects, las personas asignadas, las fechas de entrega y las actualizaciones de estado. Si aparece un problema, se registrará en la tarea correspondiente para que el equipo pueda resolverlo.

## 9. Enlaces de trabajo
- [Tablero del proyecto](https://github.com/users/Dxniel-max/projects)
- [Historias y tareas](https://github.com/Dxniel-max/registro-usuarios/issues)

---
Proyecto académico: módulo de Registro de Usuarios.
