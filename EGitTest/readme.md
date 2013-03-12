This project was based on the following tutorials: 

http://wiki.eclipse.org/EGit/User_Guide#Getting_Started

http://www.vogella.com/articles/EGit/article.html

http://eclipsesource.com/blogs/tutorials/egit-tutorial/

Observação: Para que o eclipse consiga autenticar no github via ssh, voce
deve setar a variavel HOME conforme informado no tutorial http://wiki.eclipse.org/EGit/User_Guide#Getting_Started

Se não fizer isso, não funciona!


Como importar um projeto do github, que não é um projeto eclipse pronto para ser importado, como um projeto maven local ?

É só fazer o procedimento de clonagem desse repositório: 

File > Import > Git > Projects from Git > ...

Quando vier a parte de importar o projeto, selecione o "Use the New Project Wizard"

Assim você consegue criar esse projeto como um projeto maven, java, etc...

Após ter criado o projeto. Você deve habilitar o GIT para ele. Botao direito no projeto,

team > shareproject > GIT

Então você deve selecionar em REPOSITORY o repositório já existente que você acabou de clonar do github.


Branches:



