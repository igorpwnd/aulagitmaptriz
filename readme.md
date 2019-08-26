# Comandos do Git

## Clone
Usado para clonar um repositório que se encontra remoto (no servidor do git) para o seu computador.

```git clone https://github.com/igorpwnd/aulagitmaptriz.git```

## Add/Rm
*add*\
Adiciona arquivo ou diretório

*rm*\
Remove arquivo ou diretório

```git add .```\
```git rm .```

No lugar do ponto pode ser o nome do arquivo/diretório que você quer remover ou adicionar da seleção para o commit.

## Commit 
Commit é a operação realizada onde confirmam-se as mudanças selecionadas ou removidas com os comandos **add** ou **rm**. Normalmente, coloca-se uma mensagem junto ao commit para poder identificá-los.

```git commit -m "Mensagem que você deseja"```

## Push
Envia para o servidor remoto todos os commits que se realizados anteriormente 

```git push origin nome_da_branch```

## Pull
Traz todas as novas modificações feitas na branch em questão

```git pull origin nome_da_branch```

------------

## Como transicionar entre commits