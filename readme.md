# Práctica GIT

### Lorenzo Soriano, Daniel

# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 7? ¿Por qué?**

`git checkout` 

Porque así cambio de la rama ''master'' a la rama ''styled''.

--

**2. ¿Qué comando o comandos utilizaste en el paso 10? ¿Por qué?**

`git add , git status y git commit -m` 

Para añadir el archivo ''don-quijote.md'' al staging area, luego compruebo que esté con git status y finalmente lo paso al repositorio.

--

**3. ¿Qué comando o comandos utilizaste en el paso 11? ¿Por qué?**

`git reset HEAD~1` 

Para deshacer el último commit que he hecho.

--

**4. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reset --hard`

Rehago el último commit que deshice sacándolo con git reflog.

--

**5. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
`git merge`
Para absorber la rama en la que no estoy y unir las ramas ''master'' y ''styled''.

No causa ningún conflicto.

--

**6. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**`git checkout y git merge`
Para que la rama ''styled'' absorba a la rama ''htmlify'' y se unan.

Sí causa un conflicto.

--

**7. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
`git checkout y git merge`
Para que la rama " master absorba la rama "styled".--
**8. ¿Qué comando o comandos utilizaste en el paso 25?**`git graph`

--

**9. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**`git merge --no-ff title`
Sí que podría ser, porque al styled ser hija de la rama master puede acceder igualmente a la rama padre.

--

**10. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**11. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- don-quijote.md`

--

**12. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -d title`

--

**13. ¿Qué comando o comandos utilizaste en el paso 30?**
`git reset --hard dd3268d`

--

**14. ¿Qué comando o comandos usaste en el paso 32?**

`git reset --hard f3c94b9`

--

**15. ¿Qué comando o comandos usaste en el paso 33?**

`git reset --hard a780eb7`