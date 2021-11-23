# AtividadeGQSW
Iniciar um repositorio local

 git init

Configurar user.name local e o user.email local

 git config --local user.name
 git config --local user.email

Verificar mudanças nos arquivos 

 git status

Adicionar os arquivos modificados para o estado staged

 git add nome_do_arquivo

Fazendo um commit das alterações e movendo-os para o estado committed

git commit -m "Descrição do commit"


Comando para ver a árvore de commits

 git log
 git log --oneline ( para ver uma descrição mais curta dos commits )

Adicionando o repositorio ( GitHub )

git remote add origin url_repositorio_remoto

Criando uma branch 

git checkout nome_da_branch
git checkout -b nome_da_branch ( Criando e branch e já mudando para ela usa-se a flag -b )

Ver todas as branchs 

git branch

Subindo todas as mundanças do repositório local para o remoto

git push origin nome_da_branch

