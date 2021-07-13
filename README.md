# Projeto: Analise de fraude em transações imobiliarias
 
A análise de fraude combina tecnologia e técnicas analíticas com interação humana para ajudar a detectar possíveis transações impróprias, como aquelas com base em fraude e/ou suborno, antes que as transações sejam concluídas ou depois que elas ocorrem.

O processo de análise de fraude envolve a coleta e armazenamento de dados relevantes e explorando-o em busca de padrões, discrepâncias e anomalias.

## Definição do Problema

Uma empresa fornece seguros para imóveis na cidade de Nova Iorque nos EUA. Visando calcular o valor do seguro da melhor forma possível, a empresa deseja uma análise e detecção de fraude nos dados de transações imobiliárias de toda cidade.

Primeiro a empresa precisa de um relatório que demonstre que os dados são confiáveis e coerentes e que a qualidade da informação que eles oferecem pode ser usada para prever possíveis fraudes. Sendo assim, devemos apresentar um DQR –Data Quality Report com uma análise exploratória dos dados.

Por fim a empresa precisa de um score para cada transação a fim de checar aquelas com maior possibilidadede ter alguma fraude. O Score de Fraude (Fraud Score) deve ser o mais preciso possível e deve ser gerado um score para cada transação. Não há informação prévia se uma transação foi ou não fraudulenta.

## Escopo do Projeto

Neste projeto iremos abordar a técnica de análise de fraude com base nos dados históricos e Não temos como objetivo fazer previsões em outros dados.

Vamos avaliar as transações e para cada transação o algoritmo irá retornar uma pontuação, as pontuações mais altas podem indicar que haja algo estranho, mas não temos como afirmar, porque vamos utilizar um algoritmo não-supervisionado e não temos a resposta para treinar o algoritmo.

O algoritmo será treinado para detectar os padrões existentes e calcularemos o score utilizando equações matemáticas, que são técnicas utilizadas na prática para detectar potenciais fraudes.

Os algoritmos usados serão PCA, para redução da dimensionalidade e Deep Learning com uso de Tensorflow e Autoencoder.

## Etapas do Projeto

Este projeto foi dividido em 3 partes:

Parte 1: Vamos conhecer nossos dados e fazer uma análise exploratória das principais variáveis definidas em conjunto com o pessoal de Negócios.<br>
Parte 2: Serão realizadas as devidas limpezas, transformações das variáveis e feature engineering ou engenharia de atributos.<br>
Parte 3: É hora da modelagem, reduziremos a dimensionalidade e calcularemos o Score 1, depois aplicaremos inteligencia artificial com Autoencoder e calcularemos o score 2, por fim calcularemos o Score Final.

## Apresentação dos resultados

Os resultados serão apresentados em forma de relatório no **Power BI** aos tomadores de decisão. clique neste link para visualizar: https://bit.ly/3kgxYky

Sumário

Parte 1: Análise Exploratória

1. Importando as bibliotecas e carregando os dados<br>
2. Análise Exploratória dos dados<br>
3. Conclusão<br>

Parte2: Limpeza, transformação e Feature Engineering

1. Importando as bibliotecas e carregando os dados<br>
2. Limpeza e transformação dos dados<br>
2.1 Limpando valores ausentes da variável: ZIP<br>
2.2 Limpando valores ausentes das variáveis: FULLVAL, AVLAND, AVTOT, BLDFRONT, BLDDEPTH, LTFRONT e LTDEPTH<br>
2.3 Limpando valores ausentes da variável: STORIES<br>
3. Engenharia de Atributos<br>
4. Conclusão<br>

Parte3: Modelagem e calculo do Score de Fraude

1. Importando as bibliotecas e carregando os dados<br>
2. Padronização das variáveis<br>
3. Aplicando PCA<br>
3.1. Aplicação da Escala Z em componentes PCA Padronizados<br>
3.2 Calculando o Fraud Score 1<br>
4. Aplicacando Deep Learning<br>
4.1 Construção do Modelo<br>
4.2 Avaliação do modelo<br>
4.3 Calculando o Fraud Score 2<br>
5. Calculando o Score Final do Score de Fraude e apresentando os Resultados<br>
6. Conclusão<br>
7. Referências<br>

## Sobre os dados

Os dados são públicos e fornecidos pelo portal de dados abertos da cidade de Nova Iorque, link para baixar no notebook parte 1.

### Observação:
Este projeto foi customizado e realizado por mim com base no mini-projeto de estudo do curso de Bussiness Analytics da Data Science Academy (https://www.datascienceacademy.com.br/).
