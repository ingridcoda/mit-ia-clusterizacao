# Projeto: Validação de Modelos de Clusterização

Projeto da disciplina de **Validação de Modelos de Clusterização**, segunda disciplina do Módulo 4 da [Pós-Graduação MIT em Inteligência Artificial, Machine Learning e Deep Learning](https://posgraduacao.infnet.edu.br/ead/pos-graduacao-machine-learning-deep-learning-curso-deep-learning/) do [Instituto Infnet](https://www.infnet.edu.br/infnet/instituto/).

O projeto abrange a infraestrutura de desenvolvimento, escolha e análise exploratória de base de dados, aplicação e validação de algoritmos (K-Means e DBSCAN) e resolução de problemas teóricos sobre similaridade em séries temporais.

Desenvolvido pela aluna [Ingrid Coda](https://infnet.online/members/ingrid_codahotmail-com-2/).

---

## Enunciado do Projeto

##### (O enunciado pode ser encontrado no [Moodle da disciplina](https://lms.infnet.edu.br/moodle/mod/assign/view.php?id=461645))

> **Validação de Modelos de Clusterização — Projeto da Disciplina**
>
> O trabalho está dividido em 4 partes principais:
>
> ### Parte 1 — Infraestrutura
>
> 1. Executar os códigos em um notebook Jupyter, rodando em ambiente local.
> 2. Garantir os seguintes requisitos:
>    - Python versão 3.9 ou superior.
>    - Uso de ambiente virtual (Virtualenv ou Anaconda).
>    - Todas as bibliotecas instaladas no ambiente virtual específico.
>    - Geração do arquivo `requirements.txt` contendo as versões dos pacotes.
>    - Evidência (printscreen) do ambiente rodando localmente.
>    - Disponibilização do código, artefatos e instruções em repositório público Git.
>
> ### Parte 2 — Escolha de base de dados
>
> 1. **Seleção de Dados:** Escolher uma base de dados adequada para um problema de clusterização.
> 2. **Justificativa:** Escrever a motivação e os objetivos para a escolha destes dados.
> 3. **Análise Exploratória:** Apresentar gráficos da faixa dinâmica das variáveis. Analisar os resultados e definir o tratamento necessário antes da clusterização.
> 4. **Pré-processamento:** Realizar e descrever o pré-processamento adequado dos dados.
>
> ### Parte 3 — Clusterização e Validação
>
> 1. **Modelagem:** Realizar o agrupamento dos dados pré-processados utilizando:
>    - **K-Médias (K-Means)**
>    - **DBSCAN**
> 2. **Índice de Silhueta:** Descrever o processo de mensuração, mostrar o gráfico e justificar a escolha do número ótimo de clusters baseando-se neste índice.
> 3. **Comparação:** Comparar os resultados dos dois algoritmos (K-Means vs DBSCAN), apontando semelhanças, diferenças e interpretações.
> 4. **Outras Métricas:** Escolher mais **duas medidas de validação** (ex: Davies-Bouldin, Calinski-Harabasz) para comparar com a Silhueta e analisar os resultados.
> 5. **Análise Crítica:** Responder à questão: *"A silhueta é um índice indicado para escolher o número de clusters para o algoritmo de DBScan?"*
>
> ### Parte 4 — Medidas de Similaridade (Teoria)
>
> 1. **Cenário:** Dado um problema com 10 séries temporais distintas que devem ser agrupadas em 3 grupos baseados na correlação cruzada máxima.
>    - Descrever em tópicos os passos necessários para estabelecer a correlação cruzada como medida de similaridade.
> 2. **Algoritmo:** Indicar e justificar qual algoritmo de clusterização seria adequado para este problema.
> 3. **Aplicação:** Indicar um caso de uso prático para essa solução.
> 4. **Alternativa:** Sugerir e descrever em tópicos outra estratégia para medir a similaridade entre séries temporais.

---

## Como rodar localmente

1. Clone o repositório do GitHub.
2. Crie um ambiente virtual Python (Virtualenv ou Anaconda).
3. Instale as dependências listadas no arquivo `requirements.txt`.
4. Baixe o dataset "Country-data.csv" do Kaggle e coloque-o na pasta apropriada, ou configure sua API do Kaggle para download automático.
5. Execute o notebook principal (`IngridOrnellasCodaSantAnnaGomes_ValidacaoDeModelosDeClusterizacao_pd.ipynb`) utilizando Jupyter Lab, Jupyter Notebook ou em alguma IDE compatível de sua preferência.

