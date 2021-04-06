# ing-lab-4

## Trabajo Practico N1

### __1- Descargar Git y eleccion de IDE__

* Descargar e instalar Git
* Elegir IDE como cliente visual. En mi caso elegi Visual Studio Code.

### __2- Crear un repositorio local y agregar archivos__

* Creamos un repositorio local en un directorio de nuestra pc.

    ![](assets/repoLocal.png "Creo un repo local")

* Agregamos un archivo Readme.md, que contenga tu nombre y un link a nuestro CV.md. Este ultimo estara al mismo nivel de carpeta .
    * [Readme.md](https://github.com/KevinGenaro/TP1-SistemasDeControlDeVersiones)
    * [Mi Curriculum Vitae](https://github.com/KevinGenaro/TP1-SistemasDeControlDeVersiones/blob/master/CV.md)

    ![](assets/agregarArchivosyCommit.png "se agregan archivos y se hace el primer commit")

### __3- Crear un repositorio remoto__

* Creamos un nuevo repositorio en Github (vacío)

* Asociamos el repositorio local con el repositorio de Github.
* Subimos los cambios locales a Github.

    ![](assets/asociarRepo.png "link del repo local al remoto y push del commit")

### __4- Familiarizarse con el concepto de Pull Request__

* Creamos un branch local y agregamos cambios a dicho branch
    

     ![](assets/4.png "Creo un branch con el nombre dev")

* [Pull Request](https://github.com/KevinGenaro/TP1-SistemasDeControlDeVersiones/blob/master/PR.md)

* Subimos el cambio a dicho branch y creamos un nuevo pull request.

    ![](assets/5.png "creamos PR con el agregado del archivo PR.md y tambien una modificacion en el README")


    ![](assets/6.png "creamos PR con el agregado del archivo PR.md y tambien una modificacion en el README")


    ![](assets/7.png "creamos PR con el agregado del archivo PR.md y tambien una modificacion en el README")

* Completamos el proceso de revisión en github y mergeamos el PR a la rama master.

    ![](assets/8.png "por ultimo hacemos merge de las dos ramas")



### __5- Mergear código con conflictos__

*   Clonamos en un segundo directorio de nuestro equipo el repositorio creado en Github.
*   En el clone inicial, modificamos el CV.md cambiando algunas lineas.
*   Hacemos commit y subimos el cambio a master en Github.
*   En el segundo clone también realizamos cambios en las mismas líneas que se modificaron en el otro directorio.
*   Intentamos subir el cambio, haciendo un commit y luego un push. Se genera un error que detallamos mas abajo.

    ![](assets/9.png "intentamos pushear a master desde el CLONE que realizamos y nos genera conflicto ya que modificamos las mismas lineas en ambos clones")

    ![](assets/10.png "podemos ver el conflicto generado y el ide nos especifica el current change y upcoming change")

*   Resolvemos los conflictos del código eligiendo que change queremos sostener.
*   Explicamos las versiones LOCAL, BASE y REMOTE dentro de nuestro README.
    * [LOCAL, BASE, REMOTO](https://github.com/KevinGenaro/TP1-SistemasDeControlDeVersiones)      
*   Pusheamos el cambio mergeado.

     ![](assets/11.png "Se resuelve el conflicto y se pushea los cambios")

### __6- Algunos ejercicios online__

*   Para finalizar entramos a la página https://learngitbranching.js.org/
*   Completamos los ejercicios Introduction Sequence

    ![](assets/12.png "resolvemos los ejercicios introductorios")

