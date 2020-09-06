# Notebooks

Notebooks para as atividades em classe. 

## Conteúdo

1. Introdução, tipos de dados e Variáveis Visuais <br/>
   <small>
     [Pré Visualização - Jupyter Notebook](https://nbviewer.jupyter.org/github/tiagodavi70/vl-altair-tutorial/blob/b9fbe725da0cf554c7608586f490afaa6d71cd10/notebooks/Altair_1_Introducao.ipynb) |
     [Abrir no Colab](https://colab.research.google.com/github/tiagodavi70/vl-altair-tutorial/blob/master/notebooks/Altair_1_Introducao.ipynb)
   </small>

2. Transformações e Personalização <br/>
   <small>
     [Pré Visualização - Jupyter Notebook](https://nbviewer.jupyter.org/github/tiagodavi70/vl-altair-tutorial/blob/b9fbe725da0cf554c7608586f490afaa6d71cd10/notebooks/Altair_2_Dados.ipynb) |
     [Abrir no Colab](https://colab.research.google.com/github/tiagodavi70/vl-altair-tutorial/blob/master/notebooks/Altair_2_Dados.ipynb)
   </small>

3. Múltiplas Visões<br/>
   <small>
     [Pré Visualização - Jupyter Notebook](https://nbviewer.jupyter.org/github/tiagodavi70/vl-altair-tutorial/blob/b9fbe725da0cf554c7608586f490afaa6d71cd10/notebooks/Altair_3_Visoes.ipynb) |
     [Abrir no Colab](https://colab.research.google.com/github/tiagodavi70/vl-altair-tutorial/blob/master/notebooks/Altair_3_Visoes.ipynb)
   </small>

4. Interação<br/>
   <small>
     [Pré Visualização - Jupyter Notebook](https://nbviewer.jupyter.org/github/tiagodavi70/vl-altair-tutorial/blob/b9fbe725da0cf554c7608586f490afaa6d71cd10/notebooks/Altair_4_Interacao.ipynb) |
     [Abrir no Colab](https://colab.research.google.com/github/tiagodavi70/vl-altair-tutorial/blob/master/notebooks/Altair_4_Interacao.ipynb)
   </small>

5. Cartografia<br/>
   <small>
     [Pré Visualização - Jupyter Notebook](https://nbviewer.jupyter.org/github/tiagodavi70/vl-altair-tutorial/blob/master/notebooks/Altair_5_Cartografia.ipynb) |
     [Abrir no Colab](https://colab.research.google.com/github/tiagodavi70/vl-altair-tutorial/blob/master/notebooks/Altair_5_Cartografia.ipynb)
   </small>


## Dados

<p align="justify" style="text-align: justify;">O Sistema de Coleta e Distribuição de Dados Meteorológicos do INMET (temperatura, umidade relativa do ar, direção e velocidade do vento, pressão atmosférica, precipitação, entre outras variáveis) é dotado de estações de sondagem de ar superior (radiossonda); estações meteorológicas de superfície, operadas manualmente; e a maior rede de estações automáticas da América do Sul. Tudo que é recuperado de sensores automáticos pode ser visto no conjunto de <a href="https://portal.inmet.gov.br/dadoshistoricos">dados históricos do INMET</a>.</p>

<p align="justify" style="text-align: justify;">Nós preparamos dois conjuntos desses dados históricos, do ano de 2019, o <b>completo.csv</b> tem os dados do estado do Pará, e o <b>dados.csv</b> que tem os mesmos dados agrupados por média da semana de 10 cidades das 31. O arquivo `metadados.csv` tem informações sobre as cidades. Os métodos de agrupamento estão no notebook de <a link="https://github.com/tiagodavi70/vl-altair-tutorial/blob/master/notebooks/Dados_2_Sensores_INMET.ipynb">transformação de dados de sensores do INMET</a>, que apresenta o processamento dos arquivos.</p>

<p align="justify" style="text-align: justify;">
Os arquivos de formato geográficos de topologia e geometria foram retirados dos repositórios <a href="https://github.com/marcelodeandrade/topojson-brasil">TopoJSON - Brasil</a> e <a href="https://github.com/tbrugz/geodata-br"> Geodata BR - Brasil</a>, que também tem informações sobre outros estados. </p>

<p align="justify" style="text-align: justify;">A base sobre <a href="http://dados.gov.br/dataset/convenios/resource/dfebb30a-514e-4f6b-8c93-ab13d03632d0">Turismo</a> contém dados dos convênios do Ministério do Turismo. Convênios são acordos firmados entre órgãos públicos ou entre órgãos públicos e privados para realização de atividades de interesse comum dos participantes. Os dados abrangem o período de 1999 à setembro de 2016. </p>

<p align="justify" style="text-align: justify;"> A base do primeiro notebook é referente <a href="http://dados.gov.br/dataset/serie-historica/resource/1d9ad12d-7522-4d9c-8344-d05d1696c707">Série Histórica Ministério da Defesa</a>. Essa série Histórica Global da Execução Orçamentária do Ministério da Defesa é referente ao período de 2000-2020, e se organizam baseados em Grupos de Natureza de Despesa, das unidades orçamentárias do MD.</p>


