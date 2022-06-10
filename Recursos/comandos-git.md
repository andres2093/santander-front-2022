# Crear repositorio
git init

# Agregar archivos al index
git add <filename>
git add .

# Consolidar o confirmar
git commit -m “comment”

# Agregar remoto
git remote add origin <server>

# Enviar
git push -u origin <branchName>

---------------------------------------------

# Agregar remoto
git remote add origin <server>

# Enviar
git push origin <branchName>

---------------------------------------------

# Local
git clone /path/to/repository

# Remoto
git clone <server>

---------------------------------------------

# Crear branch
git checkout -b <branchName>

# Cambiar branch
git checkout <branchName>

# Eliminar branch
git branch -d <branchName>

# Enviar branch
git push origin <branchName>

---------------------------------------------

# Actualizar
git pull

# Fusionar
git merge <branchName>

# Conflictos
git add <filename>

# Comparar branch's
git diff <source_brach> <target_branch>

---------------------------------------------

# Estado
git status

# Log
git log

# Descartar
git checkout – <filename>
git fetch origin
git reset –hard origin/master
