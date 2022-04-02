# Exercício de contribuição em um projeto usando fork

- Para realizar esse projeto, precisamos fazer um fork do repositório da {reprograma} [On13-TodasEmTech_Git](https://github.com/reprograma/On13_TodasEmTech_Git). 
Para saber mais sobre fork, [leia aqui](https://github.com/reprograma/On13-TodasEmTech_Git/blob/86ae350c27a4760f5fddf86b006cfcfa3f6b7e6c/conteudo/sobre-fork.md)

### Instruções
* Após o fork, entrar no repositório que fica na aba de "Meus Repositórios" na sua conta do Githun
* Clonar o repositório para seu computador
* Entrar na pasta 8-exercicio-projeto-casa e siga as instruções a seguir.
* Adicionar link para imagem, link para seu github e o seu nome em uma `<div>`, seguindo o modelo com as informações da Paula Allemand.
	* Use o link do seu github para colocar no ***href*** na tag `<a>`. (Ex: https://github.com/reprograma)
	* Use o link da imagem do seu avatar no github para colocar no ***src*** da tag `<img>`. Clique com o botão direito sobre a imagem do seu perfil no github e copie o endereço da imagem. (Ex: https://avatars2.githubusercontent.com/u/41296983?s=460&u=d69e452fb89212415aca4769125d7efb7fc52727&v=4)
    * Exemplo de como capturar o link da imagem:
      <img src="./readme-assets/endereco-imagem.png">

  * Adicione seu nome no ***alt*** da tag `<img>`

  Exemplo:

    **Antes:**

    ```
    <div class="container__aluna">
        <a href="#/seu-link-do-github" target="_blank">
            <img class="container__aluna-img" src="#/seu-link-da-foto" alt="">
        </a>
        <p>Seu Nome</p>
    </div>
    ```
    
    **Depois:**
    
    ```
      <div class="container__aluna">
        <a href="https://github.com/itsalle" target="_blank">
          <img class="container__aluna-img" src="https://avatars2.githubusercontent.com/u/41296983?s=460&u=d69e452fb89212415aca4769125d7efb7fc52727&v=4"
            alt="Paula Allemand">
        </a>
        <p>Paula Allemand</p>
      </div>
    ```

* Conferir essa alteração no navegador (Chrome).
	* *Comportamento esperado: ao clicar na sua foto, o link do seu github irá se abrir numa aba nova*

* Voltando para o Git Bash.
* `git diff`: verificar o que você alterou no código.
* `git status`: verificar o status (ATENÇÃO: aqui se certifique que você está na branch com seu nome)
* caso não esteja na branch com seu nome, lista todas as branchs `git branch -a`
* `git checkout branch-com-meu-nome-sobrenome`: acessar a branch com seu nome e sobrenome :)
* `git add index.html`: Adicionar as alterações para área de preparaço.
* `git status`: verificar o status novamente.
* `git commit -m "adicionando foto e link de <seu nome> para Githbub"`: adicionar mensagem de ***commit***.
* `git push origin branch-com-meu-nome-sobrenome`: subir as alterações da sua branch para o seu repositório remoto.
* Verificar se as alterações foram atualizadas no seu repositório


* Ir para a aba ***Pull requests*** do repositório da aula 
* Criar novo pull request ***New pull request***, selecionando a opção **compare across forks** da branch do seu repositório para a branch com seu nome do repositório da reprograma