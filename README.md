# Principales comandos para git

1. Comando para crear usuario
  - git config --global user.name "name"

    Con este comando hemos creado un usuario de nombre x, tambien podemos usar el mismo comando poniendo .email para asignar un email al usuario.

2. Comando para crear el repositorio 😎
- git init
  
  Este comando ejecutado dentro de la carpeta en la cual queramos crear el repositorio, lo creara y generara la carpeta oculta .git

  ![No carga la imagen](git.PNG "GIT")

1. Comando para añadir archivo al staging area
   
- git add file

  Colocando el archivo que queremos añadir al comando (. para añadir todo) añadiremos ese archivo o directorio al staging area

4. Comando para eliminar un archivo del staging area
   
- git rm --cached file
  
  Con este comando devolvemos el archivo seleccionado el principio del proceso.

5. Comando para hacer commit

- git commit -m "msj"

    Con este comando hacemos commit de todo lo que haya en la staging area.

6. Comando para hacer push🔥

  - git push

    Con este comando haremos push al repositorio remoto

7. Comando para clonar repositorio
   
- git clone repositorio_remoto
  
  Añadiendo al comando el link del repositorio remoto, haremos el push de todo lo que hay en el commit del repositorio local
   