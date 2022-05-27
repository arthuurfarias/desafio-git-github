# Criando o Diretório

O primeiro passo é a criação da pasta em seu PC. Em nosso exemplo, criamos a seguinte:

***C:\WorkSpace***

Nosso diretório do GitHub será clonado para a pasta WorkSpace.



# Criando diretório no Github

Conforme imagem a seguir, crie o diretório.



[![Imagem 01](https://github.com/arthuurfarias/desafio-git-github/blob/main/imagens/Imagem01.png?raw=true)](https://github.com/arthuurfarias/desafio-git-github/blob/main/imagens/Imagem01.png?raw=true)



Para o próximo passo, precisaremos do link do diretório criado, você pode optar por utilizar o link HTTPS, SSH ou GitHub CLI.

[![Imagem 02](https://github.com/arthuurfarias/desafio-git-github/blob/main/imagens/Imagem%2002.png?raw=true)](https://github.com/arthuurfarias/desafio-git-github/blob/main/imagens/Imagem%2002.png?raw=true)

# Iniciando Comandos no Bash

Acesse o terminal Git Bash. 

Localize a pasta: C:\WorkSpace



- Abra a pasta do *C:\WorkSpace* da seguinte forma:

```
$ cd C:\WorkSpace
```

- Clonando o diretório do Github para a pasta WorkSpace. A URL é a mesma informada na ***Imagem 02***

```
$ git clone git@github.com:arthuurfarias/desafio-git-github.git
```

- Para saber se há alguma atualização, podemos rodar o status.

```
$ git status
```

- Acesse a pasta ***\Dio*** e abra o README.md. Através deste arquivo você poderá colocar a introdução do seu projeto utilizando o Markdown.
- De volta no Git Bash, podemos colocar no Stage todos arquivos (novos, modificados e removidos) no index/stage

```
$ git add .
```

- Realize o primeiro commmit. O que fica entre aspas, deve ser a observação que deseja, caso em algum momento precise voltar atás nas alterações feitas.

```
$ git commit -m 'Atualização README'
```

- Por fim, envie para o Github com o comando push. Fazendo isso, será atualizado todos os arquivos no site, caso algum tenha sofrido alteração em seu PC.

```
$ git push origin main
```

