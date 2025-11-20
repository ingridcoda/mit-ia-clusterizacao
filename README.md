# mit-ia-clusterizacao

Projeto da disciplina de Algoritmos de Inteligência Artificial para Clusterização, segunda disciplina do Módulo 4 - Clusterização de Dados, sendo esse o último módulo da [Pós-Graduação MIT em Inteligência Artificial, Machine Learning e Deep Learning](https://posgraduacao.infnet.edu.br/ead/pos-graduacao-machine-learning-deep-learning-curso-deep-learning/) do [Instituto Infnet](https://www.infnet.edu.br/infnet/instituto/).
O projeto envolve análise exploratória, pré-processamento, aplicação dos algoritmos K-Means, K-Medoids, Hierárquico, DBSCAN e respostas teóricas sobre os métodos utilizados.
Desenvolvido pela aluna Ingrid Coda.
---

## Enunciado do Projeto
##### (O enunciado pode ser encontrado no [Moodle da disciplina](https://lms.infnet.edu.br/moodle/mod/assign/view.php?id=461649))

> **Algoritmos de Inteligência Artificial para Clusterização — Projeto da Disciplina**
>
> O trabalho está dividido em 4 partes:
>
> ### Parte 1 — Infraestrutura
>
> 1. Execute os códigos em um notebook Jupyter, rodando em ambiente local.
> 2. Certifique-se que:
>    - Está rodando Python 3.9+
>    - Está usando ambiente virtual (Virtualenv ou Anaconda)
>    - Todas as bibliotecas estão instaladas no ambiente virtual
>    - Gerou um arquivo `requirements.txt` com as versões dos pacotes
>    - Tirou um printscreen do ambiente rodando localmente
>    - Disponibilizou os códigos, artefatos e instruções em repositório público Git (ou compactado)
>
> ### Parte 2 — Escolha de base de dados
>
> 1. Baixe os dados do Kaggle: [Country-data.csv](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)
> 2. Quantos países existem no dataset?
> 3. Mostre, através de gráficos, a faixa dinâmica das variáveis usadas na clusterização. Analise os resultados. O que deve ser feito antes da clusterização?
> 4. Realize o pré-processamento adequado dos dados.
>
> ### Parte 3 — Clusterização
>
> 1. Realize o agrupamento dos países em 3 grupos usando:
>    - K-Médias (K-Means)
>    - Clusterização Hierárquica
> 2. Para o K-Médias:
>    - Interprete cada cluster:
>      - Qual a distribuição das dimensões em cada grupo?
>      - Qual país melhor representa o agrupamento? Justifique.
> 3. Para a Clusterização Hierárquica:
>    - Apresente o dendrograma e interprete os resultados.
> 4. Compare os dois resultados, aponte semelhanças e diferenças e interprete.
>
> ### Parte 4 — Escolha de algoritmos
>
> 1. Escreva em tópicos as etapas do algoritmo de K-médias até sua convergência.
> 2. Refaça o algoritmo para garantir que o cluster seja representado pelo dado mais próximo ao baricentro (medóide) em todas as iterações.
> 3. Explique por que o K-médias é sensível a outliers.
> 4. Explique por que o DBSCAN é mais robusto à presença de outliers.

---

## Como rodar localmente

1. Clone o repositório do GitHub.
2. Crie um ambiente virtual Python (Virtualenv ou Anaconda).
3. Instale as dependências listadas no arquivo `requirements.txt`.
4. Baixe o dataset "Country-data.csv" do Kaggle e coloque-o na pasta apropriada, ou configure sua API do Kaggle para download automático.
5. Execute o notebook principal (`IngridOrnellasCodaSantAnnaGomes_AlgoritmosDeInteligenciaArtificialParaClusterizacao_pd.ipynb`) utilizando Jupyter Lab, Jupyter Notebook ou em alguma IDE compatível de sua preferência.
6. As saídas dos experimentos serão salvas na pasta de resultados.

