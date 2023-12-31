# analise_exploratoria_dos_precos_de_combustiveis

**Execução**

-Para rodar o arquivo localmente, certifique-se que as variáveis "descompactar" (notebook dos preços) ou a variável "rodando_localmente" (notebook dos tributos) estão marcadas como True

-Certifique-se também de instalar as bibliotecas: pandas, numpy, matplotlib, seaborn, geopandas, xlrd e mpl_toolkits no seu ENV 

-Realizamos esse trabalho em conjunto partindo de um projeto da iniciativa Santander Coders 2023, lecionados pela ADA Tech na disciplina Técnicas de Programação I

**Projeto - Técnicas de Programação I**

-Instrutor: Alex Lima

-Auxiliar: Maurício Sobrinho

**Equipe: Gabriel Miranda, Marcus Thadeu, Ruann Campos e Thiago Caveglion**

O projeto tem como objetivos:
* Analisar de forma exploratória a série histórica de preços de combustíveis no Brasil no período de 2018.1 a 2023.1;
* Analisar de forma exploratória a série histórica de arrecadações tributárias estaduais no mesmo período;
* Relacionar ambos datasets.

**Informações importantes sobre os dois notebooks do projeto:**

- Análise_Exploratória_Combustíveis.ipynb: notebook onde construímos a análise exploratória sobre os combustíveis.
  - Pasta datasets_combustível_comprimido: onde está armazenado os datasets comprimidos dos combustíveis. Dados disponíveis em: https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/serie-historica-de-precos-de-combustiveis.
  - Pasta IBGE_Aux: onde está armazenado o dataset auxiliar com os dados de geolocalização utilizado para a construção dos mapas na análise.
-  Análise_Exploratória_Tributação.ipynb: notebook onde construímos a análise exploratória sobre as tributações dos estados.
    - Dataset_Tributos.xls: dataset utilizado para aquisão de dados referentes às tributações (dados disponíveis em: https://dados.gov.br/dados/conjuntos-dados/boletim-de-arrecadacao-dos-tributos-estaduais)
