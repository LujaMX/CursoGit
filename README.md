# CursoGit

Los comandos más importantes en GitHub se utilizan generalmente en conjunto con Git, ya que GitHub es una plataforma de alojamiento para proyectos Git. Aquí hay una lista de algunos comandos clave que puedes usar en GitHub:

1. *git clone*: Clona un repositorio desde GitHub a tu máquina local.
   
   
   git clone <url-del-repositorio>
   

2. *git add*: Agrega cambios al área de preparación para el siguiente commit.
   
   
   git add <nombre-de-archivo>
   

3. *git commit*: Guarda los cambios en el repositorio.
   
   
   git commit -m "Mensaje del commit"
   

4. *git push*: Sube los cambios locales a un repositorio remoto en GitHub.
   
   
   git push origin <nombre-de-rama>
   

5. *git pull*: Descarga los cambios desde un repositorio remoto en GitHub y los fusiona con tu rama local.
   
   
   git pull origin <nombre-de-rama>
   

6. *git branch*: Lista, crea o elimina ramas.
   
   
   git branch <nombre-de-rama>             # Crea una nueva rama
   git branch -d <nombre-de-rama>          # Elimina una rama
   git branch                              # Lista todas las ramas
   

7. *git checkout*: Cambia entre ramas o restaura archivos.
   
   
   git checkout <nombre-de-rama>           # Cambia a una rama existente
   git checkout -- <nombre-de-archivo>     # Restaura un archivo a su estado en el último commit
   

8. *git merge*: Fusiona una rama con otra.
   
   
   git merge <nombre-de-rama-a-fusionar>   # Fusiona una rama con la rama actual
   

9. *git status*: Muestra el estado de los archivos en el directorio de trabajo y el área de preparación.
   
   
   git status
   

10. *git log*: Muestra un registro de commits.
    
    
    git log
    
