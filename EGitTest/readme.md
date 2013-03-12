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

Branches são caminhos independentes que você pode dar ao seu projeto sem por em risco o projeto master.

Use branches quando você quiser contribuir com outros repositórios. Você da um fork no repositorio 
( https://help.github.com/articles/fork-a-repo ), clona ele para a sua maquina e entao cria uma branche com 
um nome sugestivo sobre o que voce quer adicionar/alterar ao projeto original. 

Assim, o projeto original que voce fez o fork permanecera intocavel na branche master, e
voce poderá trabalhar tranquilo na branch que voce criou para adicionar a feature. Apos adicionar a feauture nessa
branche e realizar os devidos commits, voce pode enviar essa branche para o repositorio do projeto original, atraves
de um pull request (https://help.github.com/articles/using-pull-requests). 

TIP: Antes de realizar o pull request para o projeto original, atualize o fork master com o projeto original e, caso haja
atualizacoes, faça o rebase da sua branche que voce esta trabalhando na adicao da feature para a branche master atualizada.



