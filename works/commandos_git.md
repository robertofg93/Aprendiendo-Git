########################################
   COMANDOS MAS UTILIZADOS EN GIT
#######################################3
 
  1- Configuraciones Generales
- Establecer tu usuario: git config --global user.name "John Doe"
- Establecer tu email: git config --global user.email johndoe@example.com
- Establecer tu editor de texto por defecto:  git config --global core.editor emacs
- Comprobar tus Configuraciones: git config --list

  2- Repositorio Git
- inicializando en un repositorio existente: git init
- añadir nuevos archivos: git add .
- verificar estado del trabajo git: git status
- borrar un archivo del directorio: git rm
- moverse/crear rama: git checkout -b <branch>
- deshacer cambios: git commit --amend