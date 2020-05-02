Github
Arquivo da aula de Git e Github para iniciantes.

				Stage status
untracked -> não reconhecido pelo git precisa ser incluido
unmodified -> existe no git sem modificação
modified -> existe modificação
staged -> area de commit
unstage -> retirar da area de commit

				command git
git status			
git add <file>			
git rm --cached <file>
git restore <file>
git commit -m "mensage"
git log --decorate --author="name specific" --graph
git shortlog -sn
git show a6ea4f16ced9f2c hash 
git diff --name-only
git checkout -b <file> -> undo changes to the file
git reset HEAD <file> --soft --mixed --hard a6ea4f16ced9f2c hash -> to unstage
git remote add origin https://github.com/luisitb/gitGithub.git
git push -u origin master
git clone 
git branch -D <nam branch> -> delete
git merge -> union branch different generetion new commit
git rebase -> union commit 
.gitignore -> igonre file
git stash list clear
git config --global alias
git tag -a 1.0.1 -m "mensage"
git revert

Option GUI git fork clone project of person