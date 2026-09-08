# Projeto para teste de possibilidades de autocomplete

## NLTK

O NLTK (Natural Language Toolkit) é uma biblioteca Python voltada para o processamento de linguagem natural (NLP). Neste projeto, ela é utilizada para tokenizar textos, trabalhar com palavras e construir modelos N-Gram, permitindo analisar a frequência e a probabilidade de palavras que podem aparecer em seguida em uma frase.

No notebook n-grams-nltk, tem um exemplo de frases que são usadas para treinar um modelo simples, para prever a próxima palavra em um contexto de AAC (Augmentative and Assistive Communication), utilizando o formato de trigramas

Para utilizá-lo, é necessário instalar as dependências em requirements.txt e, depois, rodar install-nltk.py para instalar os pacotes necessários para obter o modelo de linguagem em português, consulte: https://www.nltk.org/howto/portuguese_en.html, para entender mais sobre.

### TODO:

Incluir um banco de palavras, das opções em https://app.notion.com/p/Autocomplete-3d4ab98d7b60808fb3b4f982108b3431:

- [pt-corpus](https://github.com/nlp-compromise/pt-corpus)
- [opus](https://opus.nlpl.eu/)

Fazer uma busca de palavras entre as frases desses bancos para incrementar os exemplos de frases no contexto de AAC.
