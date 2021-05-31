# Projeto Final do módulo 1 do bootcamp de Data Science da Alura

## Motivação

Visando complementar o estudo realizado durante o Módulo 1 do bootcamp de Data Science, o Projeto Final propõe a realização de uma nova análise com dados de produção hospitalar do TabNet diferente dos utilizados durante as aulas.

## Dados

Foram utilizados dados do TabNet a partir de 2008 para a realização do estudo, com dados consultados ao final do mês de Maio de 2021. Para a realização do estudo foram utilizados os dados de Óbitos por Unidade de Federação e Ano/mês atendimento e dados do número de Internações por Unidade de Federação e Ano/mês atendimento.

## Objetivo

O objetivo do projeto foi analisar a base de dados, buscando avaliar o movimento do número de óbitos por região, avaliando se a média mensal vem reduzindo ou crescendo nos últimos anos. Adicionalmente, para avaliar se a variação do número de óbitos não é proveniente apenas da mudança do número de atendimentos, foi utilizado o banco de dados do número de internações, visando avaliar se, o número de óbitos por número de internações apresenta um movimento similar ou contrário do número de óbitos.
De forma a afunilar o estudo e aprofundar o projeto, decidiu-se por avaliar o movimento por regiões (Norte, Nordeste, Centro-Oeste, Sudeste e Sul) e, por fim, o movimento nos estados do Sudeste. Com as três análises em mãos, foi possível avaliar e comparar o movimento geral de óbitos e por atendimento em todo território nacional, com o movimento para cada região e com cada estado da região Sudeste.

## Metodologia

Primeiramente foi avaliado a evolução do número de óbitos em toda região nacional, agrupado por região e por fim para a Região Sudeste, enfoque do estudo. Foram utilizados os dados médios para cada análise criando gráficos da evolução em todo o período do estudo. Devido à diferença entre as populações de cada região, optou-se por trabalhar com os dados de óbitos por internações, permitindo assim a comparação entre as regiões. Assim, foram avaliados os mesmos gráficos de média dos valores ao decorrer do período do estudo, porém agora com dados de óbitos por internações.

## Resultados Esperados

Foi esperado resultados de um ligeiro crescimento do número de óbitos em todas as regiões, porém, quando utilizado o número de internações como parâmetro, a quantidade de óbitos por número de internações esteja menor.
Para as comparações por regiões, foi esperado diferentes movimentos entre cada região, sendo possível identificar a região que apresentou uma maior variação desde 2008.
Por fim, como resultado da análise na região Sudeste, espera-se também uma diferença para cada estado, com o Rio de Janeiro apresentando a menor redução de óbitos enquanto o Espírito Santo apresentando a maior redução. Esse resultado esperado é devido ao estudo realizado anteriormente, no qual foi identificado que o Espírito Santo tem um gasto maior, por habitante, do que o Rio de Janeiro.

## Resultados Encontrados

Diferente do esperado, o número de óbitos, mesmo em relação com o número de internações, apresentou ligeiro aumento desde 2008, indicando que a utilização dos dois parâmetros ajudou a relacionar o movimento entre as regiões com populações diferentes, entretanto não permitiu a visualização desejada.
Como esperado por conta do estudo de gasto por habitante na região sudeste, ao analisar a região Sudeste, o Estado do Rio de Janeiro apresentou uma elevação do número de óbitos maior, em comparação aos demais estados da mesma região, quando comparado em relação ao número de internações.
Diferente do imaginado, o Estado de São Paulo apresentou relativa estabilidade da relação entre número de óbitos e número de internações.


## Conclusões

Como conclusão do estudo, temos que a relação entre os parâmetros selecionados, de número de óbitos e número de internações, permitiu uma comparação entre regiões e estados com tamanho populacional diferente, diminuindo a diferença entre as regiões Sudeste e Norte, assim como dos Estados de São Paulo e Espírito Santo. Entretanto, utilizando ambos os parâmetros não foi possível identificar algum movimento interessante como uma redução do número de óbitos por internações, sendo possível apenas identificar uma ligeira estabilidade geral a partir de 2016.
Mesmo assim, foi possível identificar em todo o estudo picos próximos ao início de 2020, seja do valor absoluto de óbitos quanto o valor de óbitos por internações.
Apesar de identificar certa sazonalidade dos dados, apresentando períodos com redução de óbitos, não foi identificado nenhum padrão entre as reduções.
Como consideração final, seria interessante a utilização de mais parâmetros, tentando identificar alguma relação com o número de óbitos, podendo ser o valor gasto ou a população, procurando entender melhor se esse parâmetro está relacionado com algum outro. Ainda com os parâmetros selecionados, seria interessante uma análise da relação entre os parâmetros, procurando identificar se eles estão diretamente ou inversamente relacionados, podendo indicar o aumento de um com a queda de outro.
Ainda seria possível, seguindo as mesmas diretrizes do estudo, analisar outras Regiões e outros Estados, procurando outros movimentos.
