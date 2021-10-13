# practica_github

Participantes:

1. Alan
2.
3. Franco
4. cesar m
5. cualquier cosa

# Git mediante consola

1. Clonar repositorio

   `git clone` *"enlace del repositorio que deseas clonar"*

   Ejemplo:

   ```
   git clone https://github.com/FrancoGL/practica_github.git

2. Crear nueva rama

   `git branch`  *"Nombre rama"*

   Ejemplo:

   ```
       git branch "Aegir"
   ```

3. Cambiar/moverse a la nueva rama creada

   `git checkout` *"Nombre de la rama a la que quieres moverte"*

   Ejemplo:

    ```
    git checkout "Aegir"
    ```

4. Visualizar si un archivo fue modificado

   `git status`

   Al ejecutar dicho comando debería aparecer algo similar a los siguiente:

   ```
    On branch Aegir
    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
            modified:   README.md

    no changes added to commit (use "git add" and/or "git commit -a")
   ```

   Como se puede ver, git indicara si existe alguna modificación a los archivos.

5. Incluir los archivos modificados al área de trabajo

   `git add` *"Nombre del archivo que deseas agregar al área de trabajo"*

   Ejemplo:

   ```
      git add "README.md"
   ```

   O si se quiere agregar varios archivos al área de trabajo:
   
   ```
   git add .
   ```

6. Crear un commit

   `git commit -m` "Mensaje"

   Ejemplo:

   ```
   git commit -m "README.md actualizado"
   ```

7. Fusionar ramas

   1. Primero nos movemos a la rama principal.

      ```
      git checkout "main" #En este caso, main es el nombre de la rama principal#
      ```

   2. Usamos el siguiente comando para fusionar una rama que deseemos con la principal

      ```
      git merge "Aegir"
      ```

8. Subir cambios al repositorio en línea

   `git push origin` *"Nombre de la rama a subir"*

   Ejemplo:

   ````
   git push origin "main"
   ````

9. Eliminar una rama

   `git branch -d` *"Nombre de la rama que deseas eliminar"*

   Ejemplo:

   ```
   git branch -d "Aegir"
   ```

### Nota

Espero se entienda, cualquier error, me lo comunican, saludos!
