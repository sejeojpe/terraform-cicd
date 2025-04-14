# Registro de la limpieza de commits

1. Ejecuté `git rebase -i HEAD~2` para modificar los últimos 2 commits.
2. Cambié `pick` por `reword` en el primer commit para mejorar el mensaje.
3. Cambié `pick` por `squash` en los otros commits para fusionarlos en uno solo.
4. Guardé los cambios y edité el mensaje del commit final.
5. Subí los cambios con `git push --force` para actualizar el historial en GitHub.
