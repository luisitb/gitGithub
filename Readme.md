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
