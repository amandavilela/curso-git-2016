# Aprendendo git
Repo para o mini-curso de git ministrado no dia 08/10/2016 na XXIII Semana da Tecnologia da Fatec Sorocaba.

Instrutoras: [Amanda Vilela](https://github.com/amandavilela) & [Ana Gabriel](https://github.com/AnaaGabriel)

Slides em: http://www.slideshare.net/AmandaVileladeAlmeid/aprendendo-git-semana-da-tecnologia-fatec-2016


## tl;dr

### Instalando o git

https://git-scm.com/book/pt-br/v1/Primeiros-passos-Instalando-Git

### Configurando seu usuário
```
git config --global user.name "Amanda Vilela"
git config --global user.email amandavilelaalmeida@gmail.com
```

### Criando um repositório no github

![criando um repositório](https://help.github.com/assets/images/help/repository/repo-create.png)

Leia mais detalhes sobre configuração de repositórios [aqui](https://help.github.com/articles/create-a-repo/)

### Clonando um repositório

![clonando um repositório](https://help.github.com/assets/images/help/repository/clone-repo-clone-url-button.png)

![clonando um repositório 2](https://help.github.com/assets/images/help/repository/https-url-clone.png)

```
git clone <endereço>
```

### Commitando coisas

Após finalizar seu trabalho é hora de realizar um commit, o primeiro passo é adicionar os arquivos para o commit

```
git add arquivo1.js arquivo2.js
```

Após adicionar os arquivos o commit pode ser feito:

``` 
git commit -m "Sua bonita e explicativa mensagem de commit"
```
*Não se esqueça de escrever uma mensagem bem explicativa com mais ou menos 50 caracteres

### Enviando commits

Para enviar seus commits para o servidor remoto, utilize o push

```
git push origin master
``` 
Origin = repostório remoto

Master = branch para onde os commits serão enviados

### Forkando um repositório

Para forkar um repositório, clique no botão Fork no canto direito da tela:

![forkando um repositório](https://help.github.com/assets/images/help/repository/fork_button.jpg)

Uma cópia do repositório será feita para o seu perfil do github, após isso, basta clonar o repostório e enviar seus commits.

### Fazendo um Pull Request

Após enviar os commits para o respositório forkado é possível fazer um pull request, ou seja solicitar que suas modificações sejam enviadas para o repositório.

Para realizar um pull request, no seu repositório, clique na segunda aba __Pull Resquests__;

![criando um pull request 1](http://i.imgur.com/4T7o8cI.png)

Clique no botão __New Pull Request__;

O GitHub automaticamente encontrará as diferenças entre o seu repositório e o repositório principal. Basta preencher um título e uma descrição de acordo com as recomendações do repositório principal e clicar no botão __Create new pull request__.

![criando um pull request 3](https://help.github.com/assets/images/help/pull_requests/pullrequest-send.png)


## Aprendendo mais

- Assista [essa playlist](https://www.youtube.com/playlist?list=PLInBAd9OZCzzHBJjLFZzRl6DgUmOeG3H0)

- Leia a [documentação oficial do git](https://git-scm.com/)

- [Ajuda GitHub](https://help.github.com/)

- Aprendendo a escrever [documentos markdown](www.markdowntutorial.com/)


