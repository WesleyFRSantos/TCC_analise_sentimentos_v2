# TCC_analise_sentimentos_v2
Revisitei meu trabalho de conclusão de curso (https://github.com/WesleyFRSantos/TCC_analise_sentimentos/tree/main) a fim de trazer melhorias nos resultados utilizando novas técnicas de processamento de texto e análise de sentimentos.

1) Pontos de melhoria:
   
Quando desenvolvi a v1, não separei um conjunto de teste para realizar uma validação da performance do modelo, ficando difícil avaliar a performance dos resultados obtidos. Além disso, pretendo utilizar novas técnicas para processamento de texto. Na v1, realizei o tratamento do textos com a lib NLTK, fiz o pré processamento com a lib TFIDF e classifiquei os textos com a regressão logística da lib Sklearn. Dessa vez, utilizei os modelos pré treinados da comunidade Hugging Face.

2) Metodologia

O primeiro passo foi execuar novamente o modelo treinado na v1, porém separando um conjunto de teste para obter as métricas de performance e ter um objetivo para a v2.
