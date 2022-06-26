*Práctica GIT Bootcamp WEB13*
*Ruth González Estévez*

**Lo subo como rama master, pero como he visto que en el formulario de entregas se pide que la principal sea main y  que todo vaya ahí, creo una rama main la hago principal y mergeo en ella la rama master, ... espero que esté bien así ainss, sorryyy**

1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    
   *git reset --hard HEAD~1 para volver al commit anterior y volver al estado anterior en el working copy*

2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
   
   *git reset --hard (ref. del commit siguiente e76eb00) previa búsqueda con git reflog, reflog porque al deshacer en el paso anterior no tenemos acceso al commit al que queremos volver desde git log y --hard para recuperar los cambios en de ese fichero en el  working copy*

3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

   *no causó conflicto porque al crear el branch styled desde master coge sus commits y el commit de master es anterior al commit de la modificación del archivo. Es fast foward y nos hemos colocado en el commit último de la rama styled cuyos commits de master ya llevaba*

4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  
   *si hubo conflicto porque el branch de htmlfy lo hemos hecho desde la rama master y no tiene los cambios commiteados del fichero de la rama styled. El fichero de htmlfy y el de styled tienen diferencias al juntarse*

5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

   *no, porque styled ya llevaba los commits de master que eran anteriores, se han añadido los commits de styled posteriores a master por lo que también los cambios de archivos y ha sido fast forward*
	
6. ¿Qué comando o comandos utilizaste en el paso 25?
   *git graph*

7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
   
   *si, porque cuando hemos creado la rama title la hemos hecho desde master, esta ya había sido mergeada con la rama styled con sus commits*

8. ¿Qué comando o comandos utilizaste en el paso 27?

   *git reset HEAD~1*

9. ¿Qué comando o comandos utilizaste en el paso 28?

   *git checkout -- git-nuestro.md*

10. ¿Qué comando o comandos utilizaste en el paso 29?

   *git branch -D title*

11. ¿Qué comando o comandos utilizaste en el paso 30?

   *git reset --hard f8a4a5c*

12. ¿Qué comando o comandos usaste en el paso 32?

   *git checkout bae6773 //si queremos movernos sólo -- elegí esta opción*
   *git reset --hard bae6773 //si queremos volver al estado inicial en el working copy*

13. ¿Qué comando o comandos usaste en el punto 33?

   *git checkout 0fc36d3 //si queremos movernos sólo -- elegí esta opción*
   *git reset --hard 0fc36d3 //si queremos volver al estado inicial en el working copy*

