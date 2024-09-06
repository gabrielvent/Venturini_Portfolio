# Cientista de Dados

## Sobre mim
Londrina/PR - (43) 99976-2523 / gabriel.vent@hotmail.com

Engenheiro de Produção e Cientista de Dados, determinado e aprendo com muita facilidade. Tenho como **objetivo** aplicar meus conhecimentos e técnicas como Cientista de Dados.

#### Habilidades Técnicas: Python, Machine Learning, SQL, Power BI

## Formação
- MBA em Data Science e Analytics | Universidade de São Paulo (USP) (_2024 - 2026_)
- Formação Cientista de Dados 4.0	| Data Science Academy (DSA) (_2023 - 2025_) 		
- Bacharelado em Engenharia de Produção | Universidade Tecnológica Federal do Paraná (UTFPR) (_2019 - 2023_)

## Experiências
**Cientista de Dados @ Trucks Control (_Maio 2024 - Atual_)**
- Modelos preditivos de classificação, reconhecimento de imagens e visão computacional.
- Ciência de Dados como ferramenta para identificar fatores essenciais e prioritários

**Analista de Dados @ Litz Estratégia e Marketing (_Junho 2023 - Abril 2024_ ~ 11 meses)**
- Analisar dados de clientes visando otimizar seus resultados;
- Dashboards para diversas áreas de atuação, como varejo, franquias, serviços, entre outros;
- Otimizei em 70% a performance de dashboards e automatizei tarefas via Python;
- Modelos de Machine Learning para identificar padrões em questionários de pesquisa e elencar atributos mais importantes para serem priorizados com SHAP

**Estagiário de Suprimentos @ MSE Engenharia (_Abril 2022 - Setembro 2022_ ~ 6 meses)**
- Realizei orçamentos e negociei com fornecedores para otimizar custos das obras
- Responsável por manter os preços históricos atualizados no Banco de Dados

### Empresa Júnior
**Aprimora (_2019/2 - 2019/2_ ~ 3 meses)**
- Trainee

**MECA Jr (_2018/2 - 2019/2_ ~ 1 ano e 6 meses)**
- Atividades relacionadas a área administrativa, processos internos e burocráticos
- Atividades relacionadas a área de marketing, atrair clientes e divulgar a EJ em eventos 
  
## Projetos
### Técnicas de aprendizagem de máquina para classificação do nível de satisfação do estudante com base em seu perfil e percepção sobre uma universidade
[Em aguardo](https://drive.google.com/file/d/1mWIL1zGipppVKKieSNnN5gx_m9D8AuZQ/view?usp=sharing)

Analisei o desempenho de algoritmos de **Machine Learning** para classificar o nível de satisfação do estudante com a universidade, identificando os atributos mais importantes para os modelos. A partir de técnicas de balanceamento no conjunto de dados como _Oversampling, Undersampling_ e a combinação de ambos os métodos, em conjunto com modelos de classificação como **_Random Forest, Multilayer Perceptron, XGBoost_ e _Support Vector Machine_**, classifiquei o estudante entre promotor e detrator. Para avaliar o poder preditivo dos métodos, foram utilizadas métricas de avaliação como acurácia, _f-score_, precisão e _recall_. O melhor modelo foi a combinação de todos os modelos com o método _ensemble voting_, com uma acurácia geral de 90%, a categoria mais importante foi a de notas, com 44,84% de importância, e as variáveis mais importantes foram a satisfação com o próprio curso, a situação de moradia do estudante e a motivação do estudante para estudar.

Melhores Resultados:

![Melhores Resultados](/assets/best_scores.png)

Resultado Voting:

![Resultado Voting](/assets/voting.png)

Primeiros Atributos SHAP:

![SHAP](/assets/shap.png)

### Avaliação da satisfação de usuários de aeroportos usando aprendizagem de máquina aplicada à base de dados da Secretaria de Aviação Civil
[Publicado](http://dx.doi.org/10.14488/ENEGEP2023_TN_ST_402_1976_45823)

Este artigo relata a aplicação de técnicas de aprendizado de máquina à base de dados da Secretaria Nacional de Aviação Civil com os dados da pesquisa de satisfação de usuários de aeroportos no Brasil. Foram aplicados os métodos **_Random Forest, KNN, Decision Tree_ e _Naive Bayes_** para classificar a satisfação dos usuários, sendo o grau médio de satisfação dos entrevistados utilizado como variável de saída. A técnica de _undersampling_ foi usada para melhorar o balanceamento da base e melhorar o desempenho das técnicas. Os modelos obtiveram bom desempenho na classificação dos usuários, porém pesquisas futuras ainda serão necessárias para ajustar os parâmetros dos modelos e obter melhores resultados. A pesquisa ainda revelou que os principais fatores que afetam a satisfação são a limpeza, conforto acústico, conforto térmico e disponibilidade de sanitários nos aeroportos.

![Score Aviacao](/assets/scores_aviacao.png)


### Classificação da satisfação em relação à economia em dados latino-americanos utilizando aprendizagem de máquina
[Publicado](http://dx.doi.org/10.14488/ENEGEP2023_TN_ST_401_1975_46520)

Aplicação dos algoritmos **_Random Forest, XGBoost_ e _Support Vector Machine_** para classificar a satisfação dos latino-americanos com relação à economia de seu país. Os dados utilizados são da pesquisa realizada pela organização Latinobarômetro, e são referentes ao levantamento realizado no ano de 2020. Ao todo, foram contabilizados 23 países e mais de 20 mil entrevistados, que forneceram dados de pesquisa de opinião em relação economia, democracia, além de informações demográficas. Os resultados mostraram que a combinação dos três modelos com o método _ensemble voting_, alcançou métricas promissoras através de uma votação com peso probabilístico. Para este modelo, atingiu-se acurácia de 85%, com uma precisão de 93% e recall de 88% para a classe de “Insatisfeitos”. Entretanto, os modelos em geral tiveram limitações para a classificação daqueles que são considerados “Satisfeitos” com a economia. Os atributos mais importantes para os modelos foram “Satisfação com a democracia”, “Confiança no presidente” e “Quão justa é a distribuição de renda” foram as que que tiveram maior contribuição para os modelos.

![Score Latino](/assets/scores_latino.png)

### Técnicas de agrupamento para a análise de acidentes de trânsito na cidade de Belo Horizonte - Minas Gerais no ano de 2021
[Publicado](http://dx.doi.org/10.14488/ENEGEP2023_TN_ST_401_1975_46517)

Aaplicação de técnicas de clusterização no contexto de acidentes de trânsito na cidade de Belo Horizonte. Os dados foram disponibilizados publicamente pela prefeitura e são provenientes de boletins de ocorrência registrados pela polícia no ano de 2021. Para a criação do conjunto de dados final, foi necessária a fusão de três conjuntos preliminares, análise de instâncias faltantes e transformação de atributos, resultando em uma base processada com 4.562 instâncias e 31 variáveis para análise. Para a etapa de agrupamento, foram utilizados os métodos **_K-Means_ e _Hierárquico_** para formar os grupos de acidentes com base em suas similaridades. Identificou-se um total de seis clusters que foram discutidos do ponto de vista de suas particularidades, como tipos de acidentes, ocorrências em feriados ou vésperas, características do tempo, características da via, e vítimas fatais.

![Clusters](/assets/clusters.png)

## Publicações
1. OLIVEIRA, LEONARDO FERNANDO DE; VENTURINI, GABRIEL CARLOS; JUNIOR, NELSON ANTUNES; LIMA, RAFAEL HENRIQUE PALMA; SANTOS, BRUNO SAMWAYS DOS. AVALIAÇÃO DA SATISFAÇÃO DE USUÁRIOS DE AEROPORTOS USANDO APRENDIZAGEM DE MÁQUINA APLICADA À BASE DE DADOS DA SECRETARIA DE AVIAÇÃO CIVIL. Anais do Encontro Nacional de Engenharia de Produção. [S. l.]: ENEGEP 2023 - Encontro Nacional de Engenharia de Produção, 27 out. 2023. DOI 10.14488/enegep2023_tn_st_402_1976_45823. Disponível em: http://dx.doi.org/10.14488/ENEGEP2023_TN_ST_402_1976_45823.
2. TAUIL, YASSER BULATY; VENTURINI, GABRIEL CARLOS; SANTOS, HENRIQUE SARTORELLO; SANTOS, BRUNO SAMWAYS DOS. CLASSIFICAÇÃO DA SATISFAÇÃO EM RELAÇÃO À ECONOMIA EM DADOS LATINO-AMERICANOS UTILIZANDO APRENDIZAGEM DE MÁQUINA. Anais do Encontro Nacional de Engenharia de Produção. [S. l.]: ENEGEP 2023 - Encontro Nacional de Engenharia de Produção, 27 out. 2023. DOI 10.14488/enegep2023_tn_st_401_1975_46520. Disponível em: http://dx.doi.org/10.14488/ENEGEP2023_TN_ST_401_1975_46520.
3. TAUIL, YASSER BULATY; VENTURINI, GABRIEL CARLOS; DIAS, MATHEUS SANTOS; SANTOS, BRUNO SAMWAYS DOS; LIMA, RAFAEL HENRIQUE PALMA. TÉCNICAS DE AGRUPAMENTO PARA A ANÁLISE DE ACIDENTES DE TR NSITO NA CIDADE DE BELO HORIZONTE - MINAS GERAIS NO ANO DE 2021. Anais do Encontro Nacional de Engenharia de Produção. [S. l.]: ENEGEP 2023 - Encontro Nacional de Engenharia de Produção, 27 out. 2023. DOI 10.14488/enegep2023_tn_st_401_1975_46517. Disponível em: http://dx.doi.org/10.14488/ENEGEP2023_TN_ST_401_1975_46517.
