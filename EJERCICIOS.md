# EJERCICIOS PARTE 2

## Ejercicio 1. Ciclo básico
**Comando:** git add notas.md && git commit -m "feat: añade notas iniciales" && git push origin main  
**Explicación:** Se creó el archivo notas.md con las asignaturas iniciales y se subió al repositorio remoto.

## Ejercicio 2. Ramas
**Comando:** git switch -c feature-tareas  
**Explicación:** Se generó una nueva rama para añadir tareas pendientes sin modificar la rama principal.

## Ejercicio 3. Borrado y restauración
**Comando:** git rm temporal.txt  
**Explicación:** Se eliminó temporal.txt del repositorio, y luego se recuperó desde el último commit usando git restore.

## Ejercicio 4. Logs y diffs
**Comando:** git log --oneline --graph --all  
**Explicación:** Muestra un historial resumido y visual de los commits realizados.  
**Comando:** git diff HEAD~1 HEAD  
**Explicación:** Permite ver las diferencias entre el último commit y el anterior.

## Ejercicio 5. Conflictos intencionados
**Comando:** git merge feature-conflicto  
**Explicación:** Se produjo un conflicto al editar la misma línea en dos ramas. Se resolvió manualmente y se registró en conflicto.md.

## Ejercicio 6. Tags
**Comando:** git tag v1.0 && git push origin --tags  
**Explicación:** Se creó un tag ligero. Posteriormente, se añadió un tag anotado v1.1 con mensaje para señalar la primera versión estable.
