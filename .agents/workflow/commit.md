# Git Commit Workflow

## Regla Principal
Nunca debes realizar un `git commit` o `git push` de forma automática sin el consentimiento explícito del usuario. 

## Pasos para hacer un commit
Cuando se haya completado una tarea o el usuario pida preparar un commit, debes seguir estrictamente este flujo:

1. **Revisión de estado**: Ejecuta `git status` o utiliza las herramientas correspondientes para verificar qué archivos han sido modificados, añadidos o eliminados.
2. **Resumen de cambios**: Presenta al usuario un resumen claro de los archivos modificados y pregúntale si desea incluirlos todos en el commit o solo algunos.
3. **Stage (Preparación)**: Una vez que el usuario confirme qué archivos incluir, añádelos al área de preparación (por ejemplo, `git add <archivos>`).
4. **Propuesta de mensaje**: Sugiere al usuario un mensaje de commit descriptivo y conciso basado en los cambios realizados. 
5. **Confirmación y ejecución**: Pregúntale al usuario si está de acuerdo con el mensaje de commit. **SOLO** cuando el usuario diga que sí, procede a ejecutar el comando `git commit -m "mensaje"`.
