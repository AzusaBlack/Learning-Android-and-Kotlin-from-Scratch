<h2> 3. Modificar seu programa </h2>
<h3>Mudar o código "Hello World" </h3>
Vamos mudar o programa para que ele faça algo um pouco diferente.

1. Mude o texto ```"Hello, world!"``` para ```"Happy Birthday!```".
2. Para executar o programa, clique no botão de execução azul ou verde no canto superior direito.
3. Na parte inferior, você verá o código ```Happy Birthday!``` exibido, conforme mostrado abaixo.
```
Happy Birthday!
```
<h3>Como funciona?</h3>
Como isso é feito? Parece código demais só para exibir algo.
<br>
Bem, se você quisesse que um amigo escrevesse "Hello World!" em um pedaço de papel, haveria muitas informações implícitas. Se você dissesse apenas "Escreva 'Hello World!' nesse pedaço de papel", ele iria supor as informações não mencionadas. Por exemplo, seu amigo presumiria que uma caneta seria necessária e que você queria que ele escrevesse usando letras. O computador não faz essas suposições. É necessário dar instruções precisas que incluam todas as etapas.
<br>
Assim como o português tem uma estrutura, o mesmo acontece com a linguagem de programação. Se você já aprendeu outro idioma, sabe o desafio de aprender a gramática, a ortografia, o vocabulário e talvez até um novo alfabeto. Aprender a programar tem desafios semelhantes, mas, felizmente, é menos complexo e muito mais lógico do que o aprendizado do português, por exemplo.
<br>
<h3>Entender as partes do programa</h3>
Agora, examine o código. Cada parte do programa tem uma finalidade específica e todas elas são necessárias para executá-lo. Vamos começar com a primeira palavra.

```
fun
```

* ```fun``` é uma palavra na linguagem de programação Kotlin. ```fun``` significa função. Uma função é uma seção de um programa que realiza uma tarefa específica.
Observação: o Kotlin tem muitas palavras especiais com significados bem específicos. Ao aprender a programar na linguagem Kotlin, essas palavras também serão aprendidas. Elas costumam ser chamadas de palavras-chave ou palavras reservadas.

```
fun main
```

* ```main``` é o nome da função. As funções têm nomes para que seja possível diferenciar umas das outras. Essa função é chamada ```main```, porque é a primeira, ou a principal, a ser chamada quando você executa o programa. Todo programa Kotlin precisa de uma função chamada ```main```.

```
fun main()
```

* O nome da função sempre é seguido por dois parênteses ```()```.
* Dentro dos parênteses, você pode colocar informações a serem usadas pela função. Essa entrada da função é chamada de "argumentos" ou ```args```. Você aprenderá mais sobre argumentos mais tarde.

```
fun main() {}
```

* Observe o par de chaves ```{}``` após os parênteses. Dentro de uma função, há um código que realiza uma tarefa. As chaves envolvem essas linhas de código.
<br>
Veja a linha de código entre as chaves:

```
println("Happy Birthday!")
```

Essa linha de código exibe o texto ```Happy Birthday!```.

* ```println``` diz ao sistema para exibir uma linha de texto.
* Dentro dos parênteses, você coloca o texto a ser exibido.
* Observe que o texto a ser exibido está entre aspas. Isso informa ao sistema que tudo dentro das aspas precisa ser exibido exatamente como especificado.
<br>
Para exibir o texto, a instrução ```println``` inteira precisa estar dentro da função ```main```.
<br>
Então é isso. O menor programa possível em Kotlin.

```
fun main() {
    println("Happy Birthday!")
}
```