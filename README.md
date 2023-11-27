## Tema:
Previsáo de numero de docentes nas escolas por município a cada ano

## Datasets:
https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/sinopses-estatisticas/educacao-basica

## Título
Avaliação do número de docentes nas escolas brasileiras por município

## Motivação
*Qual problema pensou em resolver e por que ele é relevante?*

Direcionamento de políticas públicas e verbas governamentais para a formação de docentes tendo em vista a diversidade de gênero, faixa etária, vínculo empregatício e formação acadêmica a fim de ter uma maior distribuição por município. Sendo esses dados e predições necessárias para a alocação de pessoas e recursos em regiões que apresentam déficit de docentes.

## Métodos
*Quais técnicas de aprendizagem de máquina*

**Aprendizado Supervisionado** - Visto que nós temos acesso aos atributos de entrada e saída dos algoritmos
Avaliação cruzada dos algoritmos utilizados - Para evitar conjuntos de dados homogêneos

## Experimentos
*Quais experimentos você imagina que serão realizados*

- Análise de características de docentes por região/município
- Predição do número de docentes no ano subsequente
- Estimativa da demanda de docentes por município
- Estimativa da formação acadêmica dos docentes no ano subsequente

**Quais bases de dados serão utilizadas**

Sinopse Estatística da Educação Básica dos anos entre 2000 e 2022, disponível em - https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/sinopses-estatisticas/educacao-basica

**Como pretende avaliar os resultados**

Os resultados serão avaliados utilizando métricas de avaliação de modelos de Regressão, como MSE (Mean squared error), Taxa de Correlação (R2 Score) e RMSE (Root Mean Squared Error), não se limitando a apenas estes. Além da comparação de algoritmos para identificar qual é o mais adaptado para os dados em questão.
Os algoritmos que serão avaliados são: Regressão Linear (LR), K-nearest-neighbors (KNN), Rede Neural Artificial (ANN) e Árvore de Decisão. 
