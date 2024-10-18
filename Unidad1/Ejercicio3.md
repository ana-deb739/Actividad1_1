# EJERCICIO 3

## Creación de ramas

- Crea una rama que se llame primera en un repositorio local, y ejecuta la instrucción necesaria para comprobar que se ha creado.

    ![Creacionderamas](img/1.creacionderama.PNG)
  
- Crea un nuevo fichero en esta rama y fusiónalo con la principal. ¿Se ha producido conflicto? Razona la respuesta.
  
  Creamos el fichero prueba.txt

  ![Creaciondeprueba](img/2.prueba.PNG)

    Subimos el fichero

  ![subidadeprueba](img/subidadeprueba.PNG)

    Cambiamos de rama

  ![cambioderama](img/cambioamain.PNG)

    Hacemos un git merge y podemos observar que no hay conflicto.

  ![gitmerge](img/3.gitmergeno.PNG)
  
- Borra la rama primera.

    ![Borrolaramaprimera](img/borrarprimera.PNG)
  
- Crea una rama que se llame segunda, y modifica un fichero en ella para producir un conflicto al unirlo a la rama principal. Entrega el contenido del fichero donde se ha producido el conflicto.

    Crear rama segunda

    ![ramasegunda](img/crearsegunda.PNG)

    Modifico ejemplo.txt en main

    ![ejemplomain](img/ejemplo.txtmain.PNG)

    Git add y Git commit de main

    ![ejemplomain](img/gitaddgitcommitmain.PNG)

    Modifico ejemplo.txt en segunda

    ![ejemplosegunda](img/ejemplo.txtsegunda.PNG)

    Git add y Git commit de segunda

    ![ejemplosegunda](img/gtiaddgitcommitsegunda.PNG)
  
- Soluciona el conflicto que has creado en el punto anterior y sincroniza la rama segunda en el repositorio remoto en GitHub correspondiente. Entrega una captura de pantalla donde se vea que se ha creado la rama en el repositorio de GitHub.

  Git merge

    ![Gitmerge](img/gitmergesegunda.PNG)

  Git commit

  ![Gitcommit](img/gitcommit.PNG)

  Ramas Git Hub

  ![Ramas](img/ramasgithub.PNG)

  Codigo arreglado

  ![Codigo](img/github.PNG)
