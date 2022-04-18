
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Instalação <a name="installation"></a>

Você precisará das bibliotecas de ciência de dados padrão encontradas na distribuição [Anaconda](https://docs.anaconda.com/anaconda/install/) do Python. O código deve ser executado sem problemas usando as versões 3.* do Python.

Também usaremos a biblioteca geopandas. Você pode instalar geopandas neste [link](https://geopandas.readthedocs.io/en/latest/getting_started/install.html).

GeoPandas depende dos seguintes pacotes:

- pandas
- shapely
- fiona
- pyproj

## Project Motivation<a name="motivation"></a>

Este projeto visa fazer análise e exploração dos dados e construção de algoritmos e modelos de aprendizagem de máquina que possam nos ajudar a entender os dados que foram coletados, descobrir padrões, responder perguntas e avaliar a capacidade de predi-zer o risco de queimadas no Brasil (bioma Amazônia) para datas futuras. 


## File Descriptions <a name="files"></a>

A seguir estão os arquivos disponíveis neste repositório:

* `analise_queimadas_brasil.ipynb` - um jupyter notebook contendo todas as análises realizadas.

* `inpe_2019_2022.zip`- contém o arquivo inpe_2019_2022.csv, os dados analisados pelo arquivo .ipynb. Para usá-lo corretamente, deve-se extrair e coloque-o no mesmo diretório do arquivo .ipynb.

* Dentro da pasta shapefile temos alguns arquivos, mas o arquivo shapefile `BR_Municipios_2021.shp` com mapa do Brasil por ser grande precisa ser baixado do site do - [IBGE](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/estrutura-territorial/15774-malhas.html?edicao=30138&t=acesso-ao-produto)  


## Results<a name="results"></a>

Os resultados estão o final do arquivo `analise_queimadas_brasil.ipynb`.
 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Os dados foram coletados do Instituto Nacional de Pesquisas Espaciais do Brasil - [INPE](https://queimadas.dgi.inpe.br//queimadas/dados-abertos/).

Os dados referentes ao mapa do Brasil foram coletados da página de dados abertos do - [IBGE](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/estrutura-territorial/15774-malhas.html?edicao=30138&t=acesso-ao-produto)


