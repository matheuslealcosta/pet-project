# pet-project

#### Desenvolvedores:

* [Matheus Leal Costa]().
* [Giovanne Almeida Dutra]().
* [Luan Henrrique da Silva Barboza]().
* [Lucas Ribeiro Singulare]().
* [João Pedro Norton]().

* ## Git Tutorial

### Instalação

Pra instalar, basta acessar a página de [downloads](https://git-scm.com/downloads) e seguir as instruções\
Pra se conectar, utilize os seguinte comandos: <sub>(Substitua o nome e o e-mail para o seu)<sub/>
```
git config --global user.name "nomeDeUsuario"
```
```
git config --global user.email email@email.com.br
```



### Primeira Configuração

* Pelo terminal entre na pasta onde irá guardar o projeto: cd /caminho/para/a/pasta, depois inicialize o git na pasta com o comando: `git init`

* Outro jeito de fazer o citado acima: clique com o botão direito na pasta e selecione "Git Bash Here" para abrir o terminal do git

* Crie um clone do repositório: `git clone https://github.com/matheuslealcosta/pet-project.git`

* Entre na pasta criada pelo comando clone: cd /caminho/para/a/pasta/nova

* Crie sua branch usando como o padrão o nome da feature que você está a desenvolver: `git checkout -b nome_da_feature`

* Após criada a branch você será redirecionado automaticamente a ela, neste espaço que você desenvolverá sua parte do projteto





  ### Rotina

* Adicione as alterações feitas: `git add .`

* Cheque em qual branch você está e quais alterações foram adicionadas: `git status`

* Dê um commit com uma mensagem especificando as alterações realizadas: `git commit -m "mensagem especificando o que foi feito"`

* Envie o commit feito para sua branch: `git push origin suabranch`


  ### BackEnd
  * BackEnd de desenvolvimento em php usando o framework laravel juntamente com o laravel Sail, para padronizar a api.
  * Para rodar o BackEnd instale o docker em sua maquina (é aconselhável usar o wsl do ubuntu para o windows).
  * Entre na pasta do projeto BackEnd
  * Rode `./vendor/bin/sail up` para subir as imagens do docker na sua maquina.
  * Imagens docker são: NGINX, mysql, php.
 

     
  ### FrontEnd
  * Front-end desenvolvido em React 
