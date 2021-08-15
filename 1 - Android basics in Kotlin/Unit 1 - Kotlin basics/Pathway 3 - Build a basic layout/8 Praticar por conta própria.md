<h2>8. Praticar por conta própria </h2>
Observação: os problemas práticos são opcionais. Eles oferecem uma oportunidade para você praticar o que aprendeu neste codelab.

<b>Faça o seguinte:</b>

1. Mude as instruções ```println()``` para ```print()```.
2. Execute seu programa. O que acontece?
**Dica:** a instrução ```print()``` só exibe o texto, sem adicionar uma quebra de linha no final de cada ```string```.

3. Corrija o texto para que cada parte da mensagem fique na própria linha.
<b>Dica:</b> use ```\n``` no texto para adicionar uma quebra de linha. Por exemplo: ```"quebrar \n linha"```. A adição de uma quebra de linha muda a saída conforme mostrado abaixo.

<b>Dica:</b> você pode exibir uma linha vazia se não incluir o texto: ```println("")```.

<b>Código:</b>

```
fun main() {
    println("sem quebra de linha")
    println("")
    println("quebrar \n linha")
}
```

<b>Saída:</b>

```
sem quebra de linha

quebrar
 linha
```

<b>Confira seu trabalho:</b>

Veja uma possível solução:

```
fun main() {
    print("Happy Birthday!\n")
    print("Maria\n")
    print("Você tem 25 anos!")
}
```