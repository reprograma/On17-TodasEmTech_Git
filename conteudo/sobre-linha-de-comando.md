[<- Início](../README.md)

# Linha de comando

<img src="../imgs/cli/cli.gif" alt="Logo do git" />


## Índice
- [O que é linha de comando ?](#o-que-é-linha-de-comando-)
- [Por que é importante ?](#por-que-é-importante-)
- [Comandos básicos do terminal](#comandos-básicos-do-terminal)
- [Hora do exercício](#hora-do-exercício)

### O que é linha de comando ?

É aquela tela preta que aparece nos filmes, normalmente com alguém hackeando algum sistema. Mexer com o terminal assusta um pouco porque ele não é nem um pouco visual. Mas é muito simples mexer nele. Sabe quando a gente arrasta arquivos para uma pasta ou cria uma pasta nova? No terminal você faz tudo isso também, mas sem interface gráfica. A gente insere comandos, e ele executa.

### Por que é importante ?

Na linha de comando você controla melhor o que está rolando com o seu computador - inclusive o versionamento. O git é sempre usado através de linha de comando. (O GitHub tem ferramentas visuais para uso do Git, mas é importante saber se virar pela linha de comando)

### Comandos básicos do terminal

Esses comandos servem para para listar arquivos e navegar entre pastas dentro do computador.

No windows:
- `dir` - lista (ele traz uma lista de tudo o que está naquela pasta - documentos, outras pastas, etc) 
- `cd` - change directory - entra em uma pasta, exemplos:
    - `cd ..` - volta uma pasta
    - `cd nome-da-pasta` - entra na pasta desejada
    - `cd caminho/nome-da-pasta`- entra na pasta desejada que esta dentro de outras pastas
- `mkdir` - make a directory - cria uma nova pasta, precisa colocar o nome da pasta ao executar o comando, ex:
    - `mkdir nomePastaNova`
- `> nome-do-arquivo.extensão` - criar arquivo, exemplo:
    - `> index.html`
- `cls` – limpa o terminal

No linux:

- `ls` - lista arquivos e diretórios
- `pwd` - print working directory - mostra qual é o diretorio atual 
- `cd` - change directory - entra em uma pasta, exemplos:
    - `cd ..` - volta uma pasta
    - `cd ~` - voltar para a pasta raiz
    - `cd nome-da-pasta` - entra na pasta desejada
    - `cd caminho/nome-da-pasta`- entra na pasta desejada que esta dentro de outras pastas
- `mkdir` - make a directory - cria uma nova pasta, precisa colocar o nome da pasta ao executar o comando, ex:
    - `mkdir nomePastaNova`
- `rm` - remove - deleta um arquivo. precisa indicar o nome do arquivo, exemplo:
    - `rm index.html`
- `rm -r` ou `rm --recursive`: deleta uma pasta e os arquivos dentro dela, exemplo:
    - `rm -r nomeDaPasta`
- `> nome-do-arquivo.extensão` - criar arquivo, exemplo:
    - `> index.html`
- `pasta > nome-do-arquivo.extensão` - cria o arquivo dentro da pasta deseja, exemplo:
    - `conteudo > texto.txt`
- `echo "texto" > nome-do-arquivo.extensão` - cria o arquivo e insere o conteúdo dentro dele.
    - `echo "oi" > apresentação.txt`
-`clear` – limpa a tela

### Hora do exercício:

Para praticarmos seguiremos esse [exercício](exercicios/1-exercicio-bash.md).


[<- Sobre git](sobre-git.md) | [Mais sobre Git e Github ->](sobre-github.md)