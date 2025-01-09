Neste vídeo vamos fazer várias coisas, inclusive nos colocar numa posição problemática porém vida real 🤝

De qualquer forma, o destaque da aula é um atalho para fazer novos `commit`, um atalho que possivelmente vai se tornar a forma padrão de você fazer eles 💪

#### Devo usar aspas duplas ou aspas simples ao passar a mensagem de commit  no terminal?
As duas opções terão o mesmo efeito, exceto se quisermos destacar alguma palavra especial (como o nome de alguma função ou arquivo) na mensagem de commit la no GitHub. Nesse caso, o destaque só funcionará se forem utilizadas aspas simples (`'`). Para esse destaque, nós podemos escrever a palavra entre acentos graves (`` ` ``). Por exemplo:
```
git commit -m 'adiciona arquivo `.editorconfig`'
```

Será renderizado no histórico de commits do GitHub assim:
![[Pasted image 20250109180403.png]]

Fazer isso utilizando aspas duplas acaba ativando um recurso no terminal chamado `command substitution`, que interpreta o que é passado entre os acentos grave como um comando a ser executado, passando o que é retornado da sua execução como um argumento para um outro comando.

`git commit -m 'mensagem-do-commit'`

