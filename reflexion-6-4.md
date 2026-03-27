##Explica con tus palabras la diferencia entre git merge y git rebase en cuanto al historial que generan.##

git merge fusiona las ramas poniendo los commits de la rama que se quiere fusionar a partir del último commit de la rama main,
git rebase reescribe la rama cogiendo los commits de tu rama y aplica los cambios en la rama principal.

##Indica una situación en la que preferirías usar rebase y otra en la que preferirías usar merge.##

Si quisiera tener n historial más limpio usaría rebase y git merge en caso de que quisiera mantener la estructura original.

##¿Por qué se recomienda no usar rebase sobre ramas que ya han sido compartidas con otras personas (push al remoto)?##

Porque reescribe el historial de commits.
