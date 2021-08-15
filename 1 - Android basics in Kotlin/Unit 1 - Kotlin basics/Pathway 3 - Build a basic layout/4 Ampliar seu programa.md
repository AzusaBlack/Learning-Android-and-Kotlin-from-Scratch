<h2>4. Ampliar seu programa</h2>
<h3>Exibir mais de uma mensagem</h3>
Muito bem! Você exibiu uma linha de texto usando ```println() function```. No entanto, é possível colocar quantas linhas de instruções você quiser ou precisar dentro de uma função para realizar uma tarefa.

1. Copie a linha ```println("Happy Birthday!")``` e cole-a mais duas vezes abaixo dela. Confirme se as linhas coladas estão dentro das chaves da função ```main```.
2. Mude um dos textos a serem exibidos para o seu nome.
3. Mude o outro texto a ser exibido para "Você tem 25 anos!".
<br>
Seu código será semelhante a este:

```
fun main() {
    println("Happy Birthday!")
    println("Maria")
    println("Você tem 25 anos!")
}
```
O que você espera que esse código faça quando for executado?
4. Execute seu programa para ver o que ele fará.
5. Acesse o painel de saída e você verá três linhas na janela do console, como mostrado abaixo.

```
Happy Birthday!
Jhansi
You are 25!
```
Bom trabalho!
<br>
<h3>Como lidar com erros</h3>
Cometer erros durante a programação é normal, e a maioria das ferramentas fornecerão feedback para que você possa corrigi-los. Nesta etapa, crie um erro para ver o que acontece.

1. No seu programa, remova as aspas em torno do texto ```Maria``` para que a linha fique como o exemplo exibido abaixo.

```
println(Maria)
```
2. Execute seu programa. Você verá ```Maria``` em vermelho e um ponto de exclamação ao lado da linha de código modificada, mostrando onde há um erro.
3. Veja o painel de saída. Ele mostra uma mensagem com o mesmo ícone de ponto de exclamação e a palavra Error. A seguir, há uma descrição do ```erro``` no seu código.
4. A mensagem ```Unresolved reference: Maria``` informa qual é o erro que o sistema acredita haver no código. Mesmo se você não souber o que significa a mensagem de erro, talvez consiga descobrir o que está errado. Neste caso, você sabe que a instrução ```println()``` exibe o texto. Você aprendeu anteriormente que o texto precisa estar entre aspas. Se não estiver, isso é um erro.
5. Adicione as aspas novamente.
6. Execute seu programa para confirmar se ele voltou a funcionar.
Parabéns! Você executou e modificou seu primeiro programa Kotlin.