git init	Inicializa un nuevo repositorio de Git en el directorio actual.	git init

git clone	Descarga (clona) un repositorio existente desde una URL remota.	git clone 

git status	Muestra el estado del área de trabajo y del staging area (índice).	git status

git add	Añade cambios del área de trabajo al staging area (prepara archivos para el commit).	git add nombre-del-archivo.txt o git add .

git commit	Confirma los cambios que están en el staging area y los guarda en el historial local.	git commit -m "Mensaje descriptivo"

git pull	Descarga y fusiona los cambios del repositorio remoto a la rama local.	git pull origin main

git fetch	Descarga los cambios del remoto, pero sin fusionarlos.	git fetch

git checkout	Cambia a una rama diferente (también usado para restaurar archivos).	git checkout nombre-de-la-rama

git switch	Alternativa moderna para cambiar de rama (más recomendada que checkout).	git switch main

git merge	Fusiona el historial de una rama específica en la rama actual.	git merge rama-a-fusionar

git log	Muestra el historial de commits.	git log --oneline