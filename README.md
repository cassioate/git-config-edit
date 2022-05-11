# git-config-edit
gitconfig modificado para utilização pessoal

1º Utilizar o comando: git config --global core.editor code
Dessa forma será possivel utilizar o vscode para editar as configurações do git de forma global(Significa que é para o meu usuario e nao apenas para o projeto)

2º Utilizar o comando: git config --global --edit

3º Agora insira os comandos do arquivo .gitconfig aqui do github dentro do gitconfig que apareceu no seu vscode.



OBS: 
Esse trecho de codigo é importante, pois o --wait fará com que o vscode só abra após ele carregar todas as informações necessarias, evitando assim bugs.
[core]
	editor = code --wait
  

