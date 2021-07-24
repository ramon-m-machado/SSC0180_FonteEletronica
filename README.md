# Projeto da Fonte

## Sumário
[Integrantes](#Integrantes) <br />
[Objetivo](#objetivo) <br />
[Função de cada Componente](#funcao) <br />
[Componentes](#Componentes) <br />
[Imagens](#imagens) <br />
[Links](#Links)

## Integrantes
<h4> Ramon Moreira Machado - Nº USP 12543179 <br />
Victor Lucas de Almeida Fernandes - Nº USP 12675399 </h4>

<a name="objetivo"> </a>
## Objetivo do trabalho
Partindo de uma tomada com corrente alternada de 127V (pico de 179,6V)
e frequência de 60 Hz, construir uma fonte retificadora que consiga deixar 
a corrente contínua e ajustar a tensão para valores entre 3V e 12V.


<a name="funcao"> </a>
## Função de cada Componente

* **Transformador:** 
responsável pela redução da tensão que chega da tomada. O transformador
escolhido é capaz de modificar a ddp de 127V para 15V. Como a tensão máxima 
da fonte é de 12V, escolhemos um valor superior para garantir que esse resultado
consiga ser obtido, visto que os componentes do circuito consomem tensão.

* **Ponte de diodos:** 
responsável pela retificação do circuito, ou seja, por inverter o 
semiciclo negativo da corrente alternada. Assim, o circuito é abastecido com a corrente 
em ambos os semiciclos da corrente. No entanto, ainda existe variação na tensão, decorrente
da troca entre os semiciclos.


* **Capacitor:** 

Como o capacitor armazena uma certa carga, no circuito ele é usado como filtro, pois o tempo de descarga do capacitor é maior que o período do sinal de entrada, então ele fornece carga para o circuito quando a corrente alternada passa do pico e diminui significativamente, logo, ele é responsavel por diminuir a variação de tensão no circuito.
<br />
responsável pela etapa de filtragem, que reduz a variação da tensão existente.
O capacitor é carregado durante a parte de crescimento da onda de corrente e descarregado
na parte de decrescimento. 

Capacitor: 
Etapa de filtragem. Como a tensão que chega é alternada, o resistor que passa a corrente fica ligando e desligando.
O que precisamos fazer é filtrar a tensão para deixar ela "constante". 
Exemplo do menino que fica abrindo e fechando a torneira quando nós queremos regar o jardim. Uma resolução é colocar uma caixa d'água entre o menino e o jardim. O que passa a oscilar é o nível da caixa, mas é possível regar "constantemente".
Ela não é verdadeira constante porque a quantidade de água que sai da torneira depende da quantidade de água que tem na caixa (e a quantidade de água na caixa oscila). Se tiver muita água na caixa, a torneira tem maior pressão. Se tiver menos, tem menor pressão. Com isso, a torneira sempre fica com água (não liga e desliga), porém não sai água em uma quantidade constante.
Se a caixa d'água fosse muito grande (capacitor infinito), a quantidade de água na caixa não seria alterada com o menino abrindo e fechando. O problema é que quanto maior a caixa, mais cara ela é. Ou seja, um capacitor infinito torna a tensão constante, mas ele é caro, e não proporciona o aprendizado de outras coisas.
Portanto, precisamos fazer contas para saber qual o menor tamanho da caixa que resolve o problema, para que tenhamos um menor custo e uma nota mais alta. 


* **Resistores:**


* **Potenciômetro:**


* **Diodo Zener:**


* **Transistor NPN**:

## Componentes

| Componente | Especificação | Valor |
| --- | --- | --- |
| Transformador | | |`R$ x`|
| Ponte de Diodos | | | |
| Capacitor | | | |
| Resistor | | | |
| Diodo Zener | | | |
| Potenciômetro | | | |
| Transistor | | | |

<a name="imagens"> </a>
## Imagens do circuito

## Links
