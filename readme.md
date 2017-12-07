# Respuestas
> ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
    git reset --hard HEAD~1  porque si hago un reset normal los cambios quedarían en el staging area

> ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git —reset hard cf0b0de para que los cambios que hice se me apliquen en mi working copy

> El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No porque sigo en la misma linea, style tiene los mismos commits que master

> El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si porque las mismas lineas estaban modificadas

> El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque hizo un fast forward

> ¿Qué comando o comandos utilizaste en el paso 25?
git log —graph

> El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
si, porque estaba en la misma linea

> ¿Qué comando o comandos utilizaste en el paso 27?
git log | git reset 3a826891b8b3c35b227857f09b379b4e9f0e4ad8

> ¿Qué comando o comandos utilizaste en el paso 28?
No tenia cambios que  descartar

> ¿Qué comando o comandos utilizaste en el paso 29?
git branch -d title

> ¿Qué comando o comandos utilizaste en el paso 30?
git reflog | git reset --hard 67e0d13

> ¿Qué comando o comandos usaste en el paso 32?
git log | git reset —hard a82234b7833410c910b7ce12dc599bd7fbfadee5

> ¿Qué comando o comandos usaste en el punto 33?
git reflog | git reset —hard 67e0d13
