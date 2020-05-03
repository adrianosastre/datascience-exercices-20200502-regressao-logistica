Respostas dos Exercícios de Múltipla Escolha

1. Exercício 1 (Aprendizagem Supervisionada - Classificação)
Qual das alternativas abaixo retrata, de forma correta, um dos principais fundamentos da aprendizagem supervisionada que visa a tarefa de classificação:

( ) a) O princípio fundamental da aprendizagem supervisionada que objetiva a classificação está nos valores discretos dos parâmetros dos modelos usados na construção dos classificadores.
( ) b) Um classificador é o processo principal na fase de análise exploratória de dados.
( ) c) O princípio fundamental da aprendizagem supervisionada que objetiva a classificação está na construção de um classificador que realiza predições contínuas sobre as variáveis explicativas.
(X) d) O princípio fundamental da aprendizagem supervisionada que objetiva a classificação está nos valores discretos da variável de saída a ser predita.


2. Exercício 2 (Fronteiras de Decisão)
Marque a alternativa correta a respeito do conceito das fronteiras de decisão, ilustrado na figura abaixo:

( ) a) As fronteiras de decisão de um classificador dependem, exclusivamente dos dados
de treinamento.
( ) b) As fronteiras de decisão de um classificador baseado em regressão logística dependem
da variância da variável de saída contínua y.
(X) c) As fronteiras de decisão de um classificador baseado em regressão logística dependem
dos parâmetros da função hipótese logística, que são obtidos a partir do processo de
treinamento.
( ) d) As fronteiras de decisão de um classificador baseado em regressão logística dependem
dos parâmetros da função hipótese logística, que são obtidos a partir do processo de
teste do classificador.


3. Exercício 3 (Interpretação do custo logístico)
As figuras abaixo ilustram o conceito de logaritmo aplicado ao custo da regressão logística, descrito analiticamente a seguir:
Marque a alternativa correta sobre o comportamento do custo por dado de treinamento.

( ) a) Se a classe de saída de um dado de treinamento y = 1 e o modelo de classificação
forneceu a predição hq (x)!0, então o custo do treinamento é mínimo, i.e., custo!0.
( ) b) Se a classe de saída de um dado de treinamento y = 0 e o modelo de classificação
forneceu a predição hq (x)!0, então o custo do treinamento é máximo, i.e., custo!¥.
(X) c) Se o resultado da função hipótese se aproxima de hq (x)!0 e a classe de saída y = 0,
então o modelo converge para a predição correta e o custo de treinamento logístico
segue a expressão 􀀀log(1􀀀hq (x)).
( ) d) Se o resultado da função hipótese se aproxima de hq (x)!1 e a classe de saída y = 1,
então o modelo não converge para a predição correta e o custo de treinamento logístico
segue a expressão 􀀀log(hq (x)).

4. Exercício 4 (Função hipótese logística)
Marque a alternativa correta a respeito da influência da função hipótese logística, mostrada
abaixo, no processo de aprendizagem baseado na minimização da função custo.

( ) a) O uso da função logística hq (x) no problema da minimização da função custo baseada
no erro quadrático médio não tem influência sobre os algoritmos de aprendizagem
como o gradiente descendente.
( ) b) O uso da função sigmoid na regressão logística torna a função custo linear.
(X) c) A função custo da regressão logística é do tipo sigmoid e, com isso, é convexa,
possibilitando a convergência dos algoritmos de aprendizagem como o gradiente descendente.
( ) d) O uso da função sigmoid torna a função hipótese logística não linear impactando o
cálculo de J(q) e fazendo com que esta tenha uma característica não convexa.

5. Exercício 5 (Interpretação de Modelos de Regressão Logística)
A Figura abaixo consiste na matriz de confusão associada aos resultados de um classificador
construído na linguagem R. Baseado nos conceitos da matriz de confusão, marque a
alternativa abaixo que retrata, corretamente, a interpretação do resultado de saída destacado
em vermelho:

(X) a) O resultado de saída sensitivity é conhecido como recall e expressa pela razão entre
os verdadeiros positivos e a soma entre os verdadeiros positivos e os falsos negativos
gerados pelo classificador.
( ) b) O resultado de saída sensitivity é conhecido como precision e expressa pela razão
entre os verdadeiros positivos e a soma entre os verdadeiros positivos e os falsos
positivos gerados pelo classificador.
( ) c) O resultado de saída sensitivity é conhecido como accuracy e expressa a acurácia do
classificador construído.
( ) d) O resultado de saída sensitivity é conhecido como recall e expressa pela razão
entre os verdadeiros positivos e a soma entre os verdadeiros positivos e os verdadeiros
negativos gerados pelo classificador.

6. Exercício 6 (Overfitting)
A figura abaixo ilustra os conceitos e características relacionadas com o problema de overfitting
por meio de três gráficos.
Marque a alternativa correta sobre as ideias transmitidas pelos gráficos em relação ao
problema de overfitting.

( ) a) O problema de overfitting ocorre sempre que usamos os modelos de regressão linear
no processo de treinamento, como no gráfico em (a).
( ) b) O gráfico em (c) transmite a ideia de ajuste aderente aos dados de treinamento e,
portanto, a melhor generalização.
(X) c) O gráfico em (a) é um na subestimação ou subajuste do modelo, por não capturar a
variabilidade dos dados em sua totalidade.
( ) d) O gráfio em (b) é um caso híbrido entre sobreajuste e, por isso, é apresenta a pior
generalização.

7. Exercício 7 (Regularização)
Sobre a expressão da função custo mostrada abaixo, marque a alternativa correta quanto ao
procedimento de regularização.

( ) a) A expressão da função custo apresentada não apresenta a modificação relacionada
com a regularização.
( ) b) O parâmetro l controla a intensidade do fator de regularização e, com isso, se l )¥
temos a situação de sobreajuste e minimização completa da função custo.
(X) c) O efeito da regularização na função custo se dá pelo termo do somatório de parâmetros.
Isso significa que a regularização maximiza os valores dos parâmetros a fim de
manter as variáveis explanatórias presentes no modelo de ML.
( ) d) A ideia da regularização consiste em manter as variáveis explanatórias do modelo,
mas reduzir os valores dos seus respectivos parâmetros, modificando J(q).