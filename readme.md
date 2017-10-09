# Práctica GIT

### Tena Benages, Ana

##  Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque si utilizo el `git reset HEAD~1`bajo un nivel pero sin perder los cambios realizados en el working copy

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

Primero un `git reflog`para encontrar el nº de referencia del commit que he borrado. Luego `git reset --hard 329ee64`para volver a recuperar hasta ese commit.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

En realidad no se produce el merge porque styled ya incluye a la rama master, al estar ser fast-forward y ser superior.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí, porque el archivo don-quijote.md presentaba versiones distintas en ambas ramas, en la rama que absorbe y en la absorbida.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No, ningún conflicto porque es un merge fast-forward.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

 El comando `git graph`

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?** 

Es fast-forward necesariamente, porque title contiene a master.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- don-quijote.md`

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -d title` y `git branch -D title`

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

Primero `git reflog` para identificar el commit que nos interesa y luego `git reset --hard c4e72ad`

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

Primero `git reflog` para identificar el commit que nos interesa y luego `git checkout 198a830`

--

**13. ¿Qué comando o comandos usaste en el paso 33?**

Primero `git reflog` y luego `git checkout c4e72ad`