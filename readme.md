-	¿Qué comando utilizaste en el paso 11? ¿Por qué?<br>
El comando ejecutado fue "git reset –-hard HEAD~1" porque se quería volver un commit
atrás donde git-nuestro.md no había sido modificado y se hace reset hard porque se
específica que se modifique el working copy.    

-	¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?<br>
Los comandos ejecutados fueron "git reflog" donde se busca el id del commit (b791bcf)
y luego se ejecuta "git reset --hard b791bcf" porque se quiere volver al commit donde
se hace la modificación del archivo git-nuestro.md (paso 10).

-	El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?<br>
Aparece mensaje "Already up-to-date" esto se debe a que no hay conflictos porque se ha realizado
un merge fast forward y se ha desplazado el puntero de rama master al commit donde está
styled donde están contenidos los cambios de master.

-	El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?<br>
Aparecen conflictos porque las ramas styled y htmlify tienen el mismo archivo git-nuestro.md
pero con diferente contenido en las mismas líneas por lo que entran en conflicto al intentar
hacer un merge fast forward por lo que se resuelven conflictos dejando la parte de styled
y se realiza un nuevo commit realizando un merge no fast forward desplazando el puntero de rama
styled y el puntero HEAD a este nuevo commit con dos padres resolviendo así los conflictos.

-	El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?<br>
Aparece mensaje "Already up-to-date" esto se debe a que no hay conflictos porque se ha realizado
un merge fast forward y se ha desplazado el puntero de rama master al commit donde está
styled donde están contenidos los cambios de master.

-	¿Qué comando o comandos utilizaste en el paso 25?<br>
Los comandos utilizados fueron "git config alias.graph "log --graph --decorate --pretty=oneline""
y "git graph" para representar el grafo.

-	El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?<br>
Si porque desplazando el puntero de rama master y el puntero HEAD al commit donde esta title
estarían contenidos todos los cambios formando una lista.

-	¿Qué comando o comandos utilizaste en el paso 27?<br>
El comando ejecutado fue "git reset HEAD ~1" para deshacer el merge anterior.

-	¿Qué comando o comandos utilizaste en el paso 28?<br>
El comando ejecutado fue "git checkout -- git-nuestro.md" para descartar cambios del staging
area.

-	¿Qué comando o comandos utilizaste en el paso 29?<br>
El comando utilizado fue "git branch –D title" para eliminar la rama title.

-	¿Qué comando o comandos utilizaste en el paso 30?<br>
Los comandos ejecutados fueron "git reflog" donde se busca el id del commit (dee3bb6)
y luego se ejecuta "git reset --hard dee3bb6" porque se quiere volver al commit del paso 30).

-	¿Qué comando o comandos usaste en el paso 32?<br>
Los comandos ejecutados fueron "git reflog" donde se busca el id del commit (cd993e6)
y luego se ejecuta "git reset --hard cd993e6" porque se quiere volver al primer commit
“Creating git-nuestro file”.

-	¿Qué comando o comandos usaste en el punto 33?<br>
Los comandos ejecutados fueron "git reflog" donde se busca el id del commit (ea684c5)
y luego se ejecuta "git reset --hard ea684c5" porque se quiere volver al commit
“Adding a title to git-nuestro file”.
