# 📊 SentimentAnalyzer - 

Seja bem-vindo ao **SentimentAnalyzer**, um projeto simples de análise de sentimentos desenvolvido por um desenvolvedor júnior. O objetivo deste projeto é analisar textos e classificá-los como **positivos**, **negativos** ou **neutros**, usando aprendizado de máquina e processamento de linguagem natural (NLP). 

## 💡 O que é o SentimentAnalyzer?

O **SentimentAnalyzer** é um programa que processa textos e tenta identificar o sentimento por trás de cada um. Se você tem um conjunto de comentários de clientes ou posts nas redes sociais, ele pode te ajudar a saber se a maioria das pessoas está satisfeita, insatisfeita ou neutra sobre determinado assunto.

Esse é um projeto bem simples, perfeito para quem quer entender o básico sobre NLP e machine learning, sem muitas complicações.

## 🚀 Funcionalidades Básicas

- **Classificação de Sentimentos**: O programa classifica cada texto como positivo, negativo ou neutro.
- **Análise em Lote**: Você pode analisar mais de um texto de uma vez, usando um arquivo CSV.
- **Visualização Básica**: Mostra a quantidade de textos em cada categoria de sentimento.

## 🛠️ Tecnologias Usadas

- **Python 3.9**
- **Bibliotecas**:
  - `nltk` para o processamento de linguagem natural.
  - `scikit-learn` para os algoritmos de machine learning.
  - `pandas` para manipulação de dados.


## ⚙️ Como Usar

Aqui está um exemplo de como utilizar o **SentimentAnalyzer** para analisar um único texto:

```python
from sentiment_analyzer import analyze_sentiment

texto = "O atendimento foi ótimo, recomendo muito!"
resultado = analyze_sentiment(texto)
print(resultado)
```

Se você quiser analisar um arquivo CSV com várias frases, basta rodar o seguinte comando:

```bash
python sentiment_analyzer.py --input caminho_do_arquivo.csv
```

## 📈 Visualizando os Resultados

Depois de rodar a análise, você verá os resultados impressos no terminal com a contagem de sentimentos positivos, negativos e neutros. Por enquanto, a visualização é bem básica, mas é um bom ponto de partida para quem está começando.

## 🛠️ O que Ainda Precisa Melhorar?

Este projeto ainda está bem no início, e há muito espaço para melhorias:
- **Aprimorar a precisão**: O modelo de machine learning usado aqui é bem básico e pode ser substituído por algo mais robusto.
- **Melhorar visualizações**: Adicionar gráficos interativos e uma interface para facilitar o uso.
- **Suporte a mais idiomas**: No momento, o projeto está configurado para funcionar com textos em português.

---

**SentimentAnalyzer** – Um projeto simples, mas cheio de potencial para melhorar com o tempo!
