# EJERCICIO 3

## Creación de ramas

- Crea una rama que se llame primera en un repositorio local, y ejecuta la instrucción necesaria para comprobar que se ha creado.

    ![Creacionderamas](https://github.com/ana-deb739/prueba_AnaDeb/blob/main/Ejercicio3/img/1.creacionderama.PNG)
  
- Crea un nuevo fichero en esta rama y fusiónalo con la principal. ¿Se ha producido conflicto? Razona la respuesta.
  
  Creamos el fichero prueba.txt

  ![Creaciondeprueba](img\2.prueba.png)

    Subimos el fichero

  ![subidadeprueba](img\subidadeprueba.png)

    Cambiamos de rama

  ![cambioderama](img\cambioamain.png)

    Hacemos un git merge y podemos observar que no hay conflicto.

  ![gitmerge](img\3.gitmergeno.png)
  
- Borra la rama primera.

    ![Borrolaramaprimera](img\borrarprimera.png)
  
- Crea una rama que se llame segunda, y modifica un fichero en ella para producir un conflicto al unirlo a la rama principal. Entrega el contenido del fichero donde se ha producido el conflicto.

    Crear rama segunda

    ![ramasegunda](img\crearsegunda.png)

    Modifico ejemplo.txt en main

    ![ejemplomain](img\ejemplo.txtmain.png)

    Git add y Git commit de main

    ![ejemplomain](img\gitaddgitcommitmain.png)

    Modifico ejemplo.txt en segunda

    ![ejemplosegunda](img\ejemplo.txtsegunda.png)

    Git add y Git commit de segunda

    ![ejemplosegunda](img\gtiaddgitcommitsegunda.png)
  
- Soluciona el conflicto que has creado en el punto anterior y sincroniza la rama segunda en el repositorio remoto en GitHub correspondiente. Entrega una captura de pantalla donde se vea que se ha creado la rama en el repositorio de GitHub.

  Git merge

    ![Gitmerge](img\gitmergesegunda.png)

  Git commit

  ![Gitcommit](img\gitcommit.png)

  Ramas Git Hub

  ![Ramas](img\ramasgithub.png)

  Codigo arreglado

  ![Codigo](img\github.png)
