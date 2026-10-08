\# 🎬 Análise de Filmes e Séries com Python



\## 📌 Sobre o projeto



Este projeto apresenta uma \*\*Análise Exploratória de Dados (EDA)\*\* realizada sobre um dataset contendo informações de filmes e séries da Netflix.



O projeto foi desenvolvido utilizando Python e ferramentas de análise e visualização de dados, passando por etapas de exploração, limpeza, pré-processamento, tratamento de inconsistências e extração de insights.



O objetivo é compreender melhor a estrutura e as características dos dados, identificando padrões e informações relevantes sobre os títulos presentes no catálogo.



\---



\## 🔎 Análise Exploratória de Dados (EDA)



A primeira etapa do projeto foi dedicada à exploração inicial do dataset para compreender sua estrutura e qualidade.



Foram realizadas análises como:



\- Verificação das informações gerais do DataFrame.

\- Identificação dos tipos de dados das colunas.

\- Verificação da quantidade de valores ausentes.

\- Identificação de registros duplicados.

\- Análise de estatísticas descritivas das colunas categóricas.

\- Verificação da estrutura e quantidade de registros do dataset.



\---



\## 🧹 Limpeza e Pré-Processamento dos Dados



Após a análise inicial, foram realizados procedimentos para melhorar a qualidade e a consistência dos dados.



As principais etapas foram:



\- Criação de uma cópia do DataFrame original para preservar os dados.

\- Conversão da coluna `release\_year` para um tipo numérico.

\- Tratamento de valores que não pudessem ser convertidos através de `errors='coerce'`.

\- Identificação de colunas com valores ausentes.

\- Preenchimento dos valores ausentes em colunas de texto com `"Não Informado"`.

\- Identificação e visualização dos registros duplicados.

\- Remoção dos registros duplicados.

\- Verificação posterior para confirmar a remoção das duplicidades.



\---



\## 📊 Análise de Outliers



Também foi realizada uma análise dos valores da coluna `release\_year` para identificar possíveis valores discrepantes.



Durante essa etapa:



\- Foram analisadas as estatísticas descritivas da coluna.

\- Foi identificado um valor de ano superior a 2025.

\- O valor considerado discrepante foi substituído por `NaN` para evitar que uma informação inconsistente interferisse nas análises posteriores.



\---



\## 🔍 Extração de Insights e Análise dos Dados



Com os dados tratados, foram realizadas análises para extrair informações relevantes do dataset.



Entre as análises realizadas estão:



\- Verificação do dataset após o processo de limpeza.

\- Identificação da quantidade total de títulos.

\- Contagem da quantidade de títulos por ano de lançamento.

\- Ordenação dos registros por ano para facilitar a análise temporal.

\- Preparação dos dados para criação das visualizações.



\---



\## 📈 Visualização dos Dados e Análise



Foram desenvolvidas visualizações utilizando \*\*Matplotlib\*\* para facilitar a interpretação dos resultados.



\### 📅 Quantidade de Títulos Lançados por Ano



Foi criado um \*\*gráfico de linha\*\* para analisar a quantidade de títulos lançados ao longo dos anos.



Essa visualização permite observar a evolução do número de títulos presentes no dataset e identificar períodos com maior concentração de lançamentos.



\### 🎬 Distribuição de Filmes e Séries



Foi criado um \*\*gráfico de pizza\*\* para representar a proporção entre filmes e séries presentes no catálogo.



A visualização apresenta tanto a quantidade relativa de cada tipo quanto sua participação percentual no dataset.



\---



\## 🛠️ Tecnologias utilizadas



\- 🐍 \*\*Python\*\*

\- 🐼 \*\*Pandas\*\* — manipulação, limpeza e análise dos dados

\- 📊 \*\*Matplotlib\*\* — criação das visualizações

\- 📓 \*\*Jupyter Notebook\*\* — desenvolvimento e documentação da análise

\- 📄 \*\*CSV\*\* — armazenamento do dataset

\- 🔧 \*\*Git\*\* — controle de versão

\- 🐙 \*\*GitHub\*\* — armazenamento e compartilhamento do projeto



\---



\## 📁 Estrutura do projeto



```text

Projeto\_AnaliseFilmes\_Python/

│

├── ProjetoFilmes.ipynb

├── netflix\_titles\_sujo.csv

├── .gitignore

└── README.md

```



\---



\## ▶️ Como executar o projeto



Clone o repositório:



```bash

git clone https://github.com/userRenan/Projeto\_AnaliseFilmes\_Python.git

```



Acesse a pasta do projeto:



```bash

cd Projeto\_AnaliseFilmes\_Python

```



Abra o arquivo `ProjetoFilmes.ipynb` utilizando o Jupyter Notebook ou JupyterLab.



Certifique-se de que o arquivo `netflix\_titles\_sujo.csv` esteja na mesma pasta do notebook para que o dataset seja carregado corretamente.



\---



\## 👨‍💻 Autor



\*\*Renan Araujo\*\*



Projeto desenvolvido como parte da minha jornada de aprendizado em \*\*Ciência de Dados, Python e Análise de Dados\*\*.

