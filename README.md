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
responsável pela etapa de filtragem. 
O capacitor é capaz de armazenar uma determinada carga, e como o seu tempo de descarga é maior
do que o período do sinal de entrada, ele alimenta o circuito quando a corrente passa do pico e diminui 
significativamente e é recarregado durante o aumento da corrente até chegar no pico. 
Assim, ele consegue diminuir a variação de tensão no circuito, o "Ripple".


Como o capacitor armazena uma certa carga, no circuito ele é usado como filtro, pois o tempo de descarga do capacitor é maior que o período do sinal de entrada, então ele fornece carga para o circuito quando a corrente alternada passa do pico e diminui significativamente, logo, ele é responsavel por diminuir a variação de tensão no circuito.
<br />

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
