-  ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
"HEAD~1" para volver al commit padre y "--hard" porque el ejercicio pide perder los cambios realizados en el work copy.

-  ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reset --hard e9a2d19
Porque había que recuperar un commit previamente descartado

-  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No. 
Porque ha sido un merge fast-forward    

-  El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí.
Porque el archivo contenía cambios en las mismas líneas.

-  El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No.
Porque fue un merge fast-fordward.

-  ¿Qué comando o comandos utilizaste en el paso 25?
git log --oneline --graph

-  El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí.
Porque ambos grafos estaban en la misma línea, no había habido bifurcación.

-  ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

-  ¿Qué comando o comandos utilizaste en el paso 28?
git restore git-nuestro.md

-  ¿Qué comando o comandos utilizaste en el paso 29?
git branch git branch -D title

-  ¿Qué comando o comandos utilizaste en el paso 30? 
git reflog
git reset --hard be667fc

-  ¿Qué comando o comandos usaste en el paso 32?
git reflog
git reset --hard 587801e

-  ¿Qué comando o comandos usaste en el punto 33?
git reflog
git reset --hard d2ea942
