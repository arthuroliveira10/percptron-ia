Este repositório contém uma implementação simples de um Perceptron, um dos modelos mais básicos de redes neurais artificiais, usado para classificação binária.
O objetivo é entender de forma prática como o perceptron funciona e qual a importância dele pra história da Inteligência Artificial.


1. Conceito

O Perceptron é o modelo mais simples de rede neural artificial.
Ele recebe várias entradas, multiplica cada uma pelos seus pesos, soma tudo e adiciona o bias. Depois, aplica uma função de ativação que decide se o resultado é 1 ou 0.
Ele é importante historicamente porque foi o primeiro passo pra criação das redes neurais modernas, sendo a base pra entender aprendizado de máquina.

2. Funcionamento

O Perceptron é considerado um classificador linear, o que significa que ele separa os dados usando uma linha (ou plano, no caso de mais dimensões).
Isso quer dizer que ele só funciona bem quando os dados podem ser divididos de forma linear.
A limitação é que ele não consegue resolver problemas não lineares, como o clássico exemplo do XOR.

3. Código

As principais etapas do processo de funcionamento do perceptron são:

Receber as entradas (inputs).

Multiplicar cada entrada pelo seu peso (weights).

Somar todos os resultados e adicionar o bias.

Aplicar uma função de ativação (nesse caso, o limiar 0).

Retornar 1 se o resultado for ≥ 0, senão retorna 0.

O código segue exatamente esses passos, mostrando de forma simples como o modelo toma decisões binárias.

4. Aplicação prática

Um exemplo real de uso de um perceptron é num sistema de recomendação simples, por exemplo, pra recomendar músicas.
Ele poderia receber dados como "gosta de trap", "ouve músicas rápidas" e "curte batidas graves", e com base nisso decidir se recomenda ou não uma nova faixa.
É útil porque é rápido e fácil de treinar pra tarefas simples.
