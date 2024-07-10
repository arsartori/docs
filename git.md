# Git

### Criar uma nova branch local
	git checkout -b <New Branch>

### Sincronizar a branch local com o GitHub
	git push --set-upstream origin <New Branch>

### Fazer um merge da Branch
	git checkout master
	git merge <branch>

### Definir configurações
	git config --global user.name "My Name"
	git config --global user.email "myemail@example.com" 
	git config --global credential.helper store
	git config --global credential.helper "cache --timeout=86400"
### Branch
	git push -d origin <nome da branch>
 	git branch -d <nome da branch>
