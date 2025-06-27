# Processamento de Linguagem Natural com NLTK

Este projeto é um exemplo prático de como utilizar a biblioteca NLTK (Natural Language Toolkit) em Python para realizar diversas tarefas de Processamento de Linguagem Natural (PLN). Ele aborda desde o pré-processamento básico de texto até a análise mais avançada, como a identificação de entidades nomeadas.

## Funcionalidades Implementadas

O notebook `NLTK.ipynb` demonstra as seguintes operações:

* **Download de Pacotes NLTK:** Configuração inicial para garantir que todos os recursos necessários do NLTK estejam disponíveis.
* **Tokenização de Sentenças:** Divisão de um texto em sentenças individuais.
* **Tokenização de Palavras:** Divisão de sentenças em palavras (tokens).
* **Remoção de Stopwords:** Filtragem de palavras comuns e de pouco significado (como artigos, preposições, etc.) em português.
* **Remoção de Pontuação:** Limpeza do texto, removendo caracteres de pontuação.
* **Análise de Frequência:** Contagem da ocorrência de cada palavra e identificação das mais comuns.
* **Stemmização (Stemming):** Redução de palavras à sua raiz (radical), usando diferentes algoritmos (Porter, Snowball, Lancaster).
* **Lemmatização (Lemmatization):** Redução de palavras à sua forma base (lema), considerando o contexto e a classe gramatical.
* **Marcação POS (Part-of-Speech Tagging):** Identificação da classe gramatical (verbo, substantivo, adjetivo, etc.) de cada palavra em inglês.
* **Reconhecimento de Entidades Nomeadas (NER - Named Entity Recognition):** Identificação e classificação de entidades (como pessoas, organizações, locais) em texto em inglês.

## Tecnologias Utilizadas

* **Python 3**
* **NLTK (Natural Language Toolkit)**
* **Jupyter Notebook**


## Exemplo de Uso

O notebook contém exemplos claros para cada funcionalidade, mostrando o texto original e o resultado após cada etapa do processamento. Por exemplo, você verá a diferença entre a stemmização e a lematização, e como as entidades nomeadas são identificadas.
