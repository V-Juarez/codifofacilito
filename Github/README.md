Hola mundo desde git en codigo facilito.

Live de cofigo facilito de git, y que hacer para aprender git
Sat Nov  7 11:29:11 HAC 2020


------------- Configuracion git inicio -----------------

	git config --list

	git config --global

	git add --all
	
	git add .

	git commit -m "mensaje"


	git push orign <master> rama 

	git log


------------ ver datos en pantalla ----------------

	git log --graph 
	
	git log --oneline
	
	git commit --amend 
	
	git commit -- amend -m "Nuevo mensaje"

	git diff

	git difftool 

Etiquetas git tag newfolder number

	git checkout  -> moverse entre las ramas

	git checkout -b example2 -> creamos a nueva rama y/o commits

	git branch -m "example2" -> Renombrar las ramas

	
------------ crear una nueva rama -----------------

	  git switch -c nombre <nueva rama>

------------ en listar las ramas ------------------

	git branch	

	git branch --list


------------ hacer un merge ----------------------

	git merge example1

	git blame archivo -> nuestra los cambios realizados 

	git blame -L5,10 README.md

	git branch -D example1 -> elimina la rama

	git checkout -> movernos en las ramas