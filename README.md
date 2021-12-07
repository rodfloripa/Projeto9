# Projeto9

Criando segmentos de clientela-Engenheiro de Machine Learning-Udacity

https://br.udacity.com/course/machine-learning-engineer-nanodegree--nd009

Neste projeto, foram aplicadas técnicas de aprendizagem não supervisionada em dados sobre gastos, coletados de clientes de uma distribuidora atacadista em Lisboa, para identificar segmentos de clientes ocultos nos dados. Primeiro, foram explorados os dados selecionando um pequeno subconjunto como amostra e determinar se alguma das categorias de produtos está altamente correlacionada com outra. Depois,os dados foram pré-processados, dimensionando cada categoria de produto e identificando (e removendo) valores aberrantes. De posse dos dados "limpos", foi aplicado PCA a eles e implementados os algoritmos de clustering para criar os segmentos. Por último, foi comparada a segmentação encontrada com uma marcação adicional e considerada a maneira como essa informação poderia auxiliar a distribuidora atacadista com futuras mudanças de serviço.

Dados: https://archive.ics.uci.edu/ml/datasets/Wholesale+customers


    Segmento do Cluster 1: Representa os clientes que compram muitos secos/molhados e leite,é o consumidor varejista.
    
    Segmento do Cluster 0: São os clientes que compram muitos alimentos frescos,com número equilibrado para compras de leite,secos/molhados,congelados.É o restaurante ou café.

![ ](https://github.com/rodfloripa/Projeto9/tree/master/customer_segments/clusters.png)
