# Solución ejercicio 1


-¿Qué comando utilizaste en el paso 11? ¿Por qué? 

**git reset --hard HEAD~1 . Para deshacer el último commit.**

-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 

**git reflog . Para visualizar los últimos movimientos.**

**git reset --hard 7eea6d4 . Para rehacer el último commit, que este caso tiene ese hash.**

-El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

**No. Already up-to-date.**

-El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 

**Si. Porque modificamos las mismas lineas de un archivo en dos ramas diferentes.**

-El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 

**No. Porque no hay ninguna modificación en master.**

-¿Qué comando o comandos utilizaste en el paso 25? 

**git log --graph**

-El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

**Si. Porque title está un commit por delante y forman una lista.**

-¿Qué comando o comandos utilizaste en el paso 27?

**git reset HEAD~1**

-¿Qué comando o comandos utilizaste en el paso 28?

**git checkout -- git-nuestro.md**

-¿Qué comando o comandos utilizaste en el paso 29?

**git branch -D title**

-¿Qué comando o comandos utilizaste en el paso 30?

**git reflog**

**git reset --hard 4144e6d**

-¿Qué comando o comandos usaste en el paso 32?

**git reflog**

**git reset --hard 7eea6d**

-¿Qué comando o comandos usaste en el punto 33?

**git reflog**

**git reset --hard 6a4e923**

