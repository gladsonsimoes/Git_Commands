# Git_Commands
Alguns comandos essenciais do Git




Colocar o email:

~~~git
git config –global user.email “seuemail@exemple.com”
~~~

Colocar o name:

~~~git
git config –global user.name seunick
~~~

Ver o email e o nickname:

~~~git
git config –list
~~~

Remover o email:

~~~git
git config –global –unset user.email
~~~

Remover o nickname:

~~~git
git config –global –unset user.email
~~~
          
 —---------------------------------------------------------------------------------------
Comandos de Pasta

listar as pastas:
~~~git       
ls
~~~

abrir a pasta    
~~~git       
cd nomedapasta/
~~~

criar pasta :
~~~git
mkdir nomedapastaparacriar
~~~

Ver pasta oculta:
~~~git
ls -a
~~~

---- 

Iniciar um arquivo git:
~~~git          
- git init
~~~

O comando git init cria um novo repositório do Git. Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio.

~~~git
- git add
~~~

O "git add ." é usado para adicionar arquivos novos e modificados mas não os deletados. Já o "git add *" é usado para adicionar arquivos novos e modificados do diretório atual (Muito semelhante ao comando anterior).


realizar um commit o arquivo para o github:

~~~git
- git commit -m “mensagem do commit”
~~~

~~~git
- git push origin main
~~~

