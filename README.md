# Análise das 10 cidades de SP com maior número de mortos por COVID-19 e suas respectivas rendas

## Objetivo
Em meio a pandemia que estamos vivendo (2020), foi verificada a necessidade de levantar as 10 cidades de SP com maior número de mortos por COVID-19 para relacionar com a renda média da população, assim como o PIB percapita. Desta forma, pode-se anailisar os dados e verificar se existe aluguma relação entre eles. 

## Resultado
As 10 cidades de SP com maior número de mortos por COVID-19 são (maior para menor):
* 01 Carapicuíba; 
* 02 Guarujá;
* 03 Jundiaí;
* 04 Diadema;
* 05 São Vicente;
* 06 São Bernardo do Campo;
* 07 Guarulhos;
* 08 São Paulo; 
* 09 Osasco;
* 10 Santos.

É possível notar que existe uma relação entre as cidades com maior número de mortos e o seu respectivo PIB percapita. A seguir é apresentada a ordem do PIB (do menor para o maior) juntamente com a posição das cidades em relação ao número de mortes:
* 05 São Vicente; 
* 01 Carapicuíba; 
* 02 Guarujá;
* 07 Guarulhos;
* 04 Diadema;
* 08 São Paulo; 
* 06 São Bernardo do Campo;
* 09 Osasco;
* 03 Jundiaí;
* 10 Santos.

Assim com o salário médio dessas cidades (do menor para o maior):
* 01 Carapicuíba; 
* 05 São Vicente; 
* 02 Guarujá;
* 07 Guarulhos;
* 04 Diadema;
* 09 Osasco;
* 10 Santos;
* 03 Jundiaí;
* 06 São Bernardo do Campo;
* 08 São Paulo.

# Para visualizar

## Tecnologias
* Folium;
* Jinja;
* Matplotlib; 
* Numpy;
* Pandas;
* Python.

## Requisitos
* <a href="https://www.python.org/downloads/">Pyhton 3.6 (ou maior)</a>
* <a href="https://jupyter.org/install">Jupyter Notebook</a>

## Instalação
* Clone este repositório a partir do comando abaixo:
<pre>git clone https://github.com/MarcioOrdonez/covid19_analysis</pre>

* Após clonar, entre na pasta do repositório:
<pre>cd covid19_analysis</pre>

* Instale o que for necessário:
<pre>pip install -r requirements.txt</pre>

* Rode o projeto:
<pre>jupyter notebook</pre>

* É aberto uma aba no seu navegador com alguns arquivos. Clique para abrir o seguinte:
<pre>Covid_19_analysis.ipynb</pre>

* A partir disso, é possível verificar os 3 gráficos gerados com as respectivas informações.

# Referência
Os dados utilizados foram tirados das fontes abaixo:

* <a href="https://infograficos.gazetadopovo.com.br/saude/ranking-do-coronavirus-por-cidades-mortes-por-milhao/?utm_source=gazeta-do-povo&utm_medium=especiais&utm_campaign=coronavirus">Mortes por COVID-19</a>
* <a href="http://www.dados.gov.br/dataset/cgeo_vw_pib_percapita">PIB per capita</a>
* <a href="https://cidades.ibge.gov.br/">Salário médio</a>

# Autores
* <a href="https://github.com/brunatotti">Bruna Totti</a>
* <a href="https://github.com/MarcioOrdonez/">Marcio Ordonez</a>




