## Tema:
Previsão de numero de docentes nas escolas por município a cada ano

## Datasets:
https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/sinopses-estatisticas/educacao-basica

## Título
Avaliação do número de docentes nas escolas brasileiras por município

## Motivação
*Qual problema pensou em resolver e por que ele é relevante?*

Este trabalho tem como objetivo identificar oportunidades para direcionamento de políticas públicas e verbas governamentais para a formação de docentes tendo em vista a diversidade de gênero e faixa etária a fim de ter uma maior distribuição por município. Sendo esses dados e predições necessárias para a alocação de pessoas e recursos em regiões que apresentam déficit de docentes.

## Relevância

Tendo em vista a necessidade de formação de pessoas no ensino básico e médio, é essencial fazer uma previsão de como esses profissionais estão sendo alocados e formados por município para que se possa basear políticas públicas e promover ou direcionar profissionais para uma determinada região a depender da demanda.

O problema de previsão de população, seja população de um país, estado, empresa, área de atuação, entre outros segmentos de pessoas, é amplamente analisado para basear decisões de contratação, demissão, aposentadoria e investimentos. Dessa forma, a predição feita nesse projeto tem como objetivo servir de insumo para essas decisões baseadas em docentes do ensino médio de escolas brasileiras separadas por município.

## Métodos
*Quais técnicas de aprendizagem de máquina*

**Aprendizado Supervisionado** - Visto que nós temos acesso aos atributos de entrada e saída dos algoritmos
Avaliação cruzada dos algoritmos utilizados - Para evitar conjuntos de dados homogêneos

## Experimentos
*Quais experimentos você imagina que serão realizados*

- Análise de características de docentes por região/município
- Predição do número de docentes no ano subsequente
- Estimativa da demanda de docentes por município

**Quais bases de dados serão utilizadas**

Sinopse Estatística da Educação Básica dos anos entre 2000 e 2022, disponível em - https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/sinopses-estatisticas/educacao-basica

**Como pretende avaliar os resultados**

Os resultados serão avaliados utilizando métricas de avaliação de modelos de Regressão, como MSE (Mean squared error), Taxa de Correlação (R2 Score) e RMSE (Root Mean Squared Error), não se limitando a apenas estes. Além da comparação de algoritmos para identificar qual é o mais adaptado para os dados em questão.
Os algoritmos que serão avaliados são: Regressão Linear (LR), K-nearest-neighbors (KNN), Rede Neural Artificial (ANN) e Árvore de Decisão. 

## Referências

[Wang, C.-Y., Lee, S.-J.,Regional Population Forecast and Analysis Based on Machine Learning, Strategy. Entropy 2021, 23, 656. https://doi.org/10.3390/e23060656](https://pdfs.semanticscholar.org/ed4d/633d23da8e4d69ae4b63008b8acc5ca8c2ed.pdf)

[Şahinarslan, Fatih & Tekin, Ahmet & Cebi, Ferhan. (2021). Application of machine learning algorithms for population forecasting. International Journal of Data Science. 6. 257-270. 10.1504/IJDS.2021.10047231.](https://www.researchgate.net/publication/360183940_Application_of_machine_learning_algorithms_for_population_forecasting)

[Vankevich, Alena; Kalinouskaya, Iryna. Ensuring sustainable growth based on the artificial intelligence analysis and forecast of in-demand skills, E3S Web of Conferences; Les Ulis,  Vol. 208, (2020). DOI:10.1051/e3sconf/202020803060](https://www.proquest.com/openview/06e457a348d1454c7e3ca36ac217fcdb/1?pq-origsite=gscholar&cbl=2040555)

[Irina Grossman, Kasun Bandara, Tom Wilson, Michael Kirley, Can machine learning improve small area population forecasts? A forecast combination approach, Computers, Environment and Urban Systems, Volume 95, 2022, 101806, ISSN 0198-9715, https://doi.org/10.1016/j.compenvurbsys.2022.101806](https://www.sciencedirect.com/science/article/pii/S0198971522000503)

[Wilson, T., Grossman, I., Alexander, M. et al. Methods for Small Area Population Forecasts: State-of-the-Art and Research Needs. Popul Res Policy Rev 41, 865–898 (2022). https://doi.org/10.1007/s11113-021-09671-6](https://link.springer.com/article/10.1007/s11113-021-09671-6#citeas)

## Ferramentas de estudo

https://facebook.github.io/prophet/
