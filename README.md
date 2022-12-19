# Projeto de detecção de fraude em comprar de cartão de crédito

O objetivo deste projeto é utilizar uma base de estudos, contendo 30 variáveis resultantes de uma transformação por análise de componentes principais (PCA). A base de dados contem transações de cartões de crédito de um banco europeu durante 48h.

O desafio deste projeto está no fato da base ser altamente desbalanceada, portanto, utilizo técnicas de down e under sampling para tratar o problema. Além de toda a análise expliratória da base.

Conclusão

Neste trabalho, foi desenvolvido a avaliação do comportamento fraudulendo, a avaliação do desbalanceamento da base, o treinamento e avaliação de 5 modelos com os dados balanceados Under Sampling e a comparação do modelo de regressão logistica para o balanceamento undersample e oversample. É interessante notar que ambos os datasets estavam igualmente balanceados, Porém a uso da técnica de Undersampling em um dataset com tão poucos dados de uma das classes acababa perdendo muita informação. Ou seja, nesses casos é melhor aplicar o SMOTE e criar dados fictícios ao invés de tirar os existentes.



Obs. O projeto contem um erro conceitual, eu separei a base de treino e teste DEPOIS de realizar o down-sampling, isso é um erro. Em breve postarei uma versão do projeto com esta correção e algumas melhorias.


