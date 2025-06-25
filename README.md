
# 💬 Análise de Sentimentos com NLP usando Python

Este projeto realiza uma análise de sentimentos em avaliações textuais de produtos com técnicas de **Processamento de Linguagem Natural (NLP)**, utilizando bibliotecas como `scikit-learn`, `NLTK` e `WordCloud`. O objetivo é classificar as avaliações em **positivas** ou **negativas**, treinando modelos de machine learning com diferentes pré-processamentos.

## 🧰 Tecnologias e Bibliotecas Usadas

- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
- nltk
- wordcloud
- unidecode

## 🗂️ Estrutura do Projeto

- **Leitura e limpeza dos dados**
- **Tokenização** com `nltk`
- **Remoção de stopwords, pontuações e acentuação**
- **Normalização** de texto (minúsculas e stemming)
- **Visualização com WordCloud e gráficos de frequência**
- **Vetorização com CountVectorizer e TF-IDF**
- **Criação de modelo com Regressão Logística**
- **Uso de n-grams para melhorar a representação textual**
- **Avaliação de performance do modelo**

## 🧪 Pré-processamentos aplicados

1. Remoção de `stopwords` e `pontuações`
2. Remoção de acentos (`unidecode`)
3. Conversão para **minúsculas**
4. Aplicação de **stemming** com `RSLPStemmer`
5. Geração de n-grams com `TfidfVectorizer(ngram_range=(1, 2))`

## 🔍 Resultados

Acurácia dos modelos:
- Bag of Words simples: `~X.XX`
- TF-IDF com stemming: `~X.XX`
- TF-IDF com n-grams (1,2): `~X.XX`

> As palavras mais associadas a sentimentos positivos e negativos também são extraídas com base nos pesos do modelo.

## 📊 Visualizações

- **WordCloud** para sentimentos positivos e negativos
- **Gráficos de frequência** das palavras mais comuns

## 📁 Dados

Os dados utilizados devem estar em um arquivo CSV com as colunas:
- `review_text`: texto da avaliação
- `polarity`: 0 (negativo) ou 1 (positivo)

> O dataset utilizado foi o `b2w.csv`.

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o código em um notebook Jupyter ou Google Colab.

## 📝 Autor

Feito por [Seu Nome](https://github.com/GustavoMiec) — projeto acadêmico de IA e NLP.
