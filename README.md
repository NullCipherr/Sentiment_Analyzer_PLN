# 📊 Análise de Sentimentos PLN

Bem-vindo ao repositório de Análise de Sentimentos! Este projeto utiliza técnicas de Processamento de Linguagem Natural (PLN) para classificar sentimentos em textos. O código é escrito em Python e utiliza bibliotecas populares como `scikit-learn`, `nltk` e `pandas`.

## 🌟 Características Principais

- 📚 **Pré-processamento de Texto**: Tokenização, remoção de stopwords e conversão para minúsculas.
- 🔍 **Modelo de Classificação**: Utiliza o algoritmo Naive Bayes com TF-IDF para a classificação de sentimentos.
- 📈 **Validação Cruzada**: Avaliação do modelo com validação cruzada (k-fold) para garantir a robustez dos resultados.
- 📊 **Avaliação de Desempenho**: Relatórios de classificação e matrizes de confusão para avaliar o desempenho do modelo.
- 🔄 **Grid Search**: Ajuste de hiperparâmetros para otimizar o desempenho do modelo.

## 📂 Estrutura do Repositório

- `training.csv`: Arquivo de dados de treinamento.
- `validation.csv`: Arquivo de dados de validação.
- `main.py`: Script principal que contém o código para pré-processamento, treinamento, validação e avaliação do modelo.
- `requirements.txt`: Arquivo com as dependências necessárias para executar o código.

## 🚀 Como Executar

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/NulCipherr/Sentiment_Analyzer_PLN.git
   cd Sentiment_Analyzer_PLN
   ```

2. **Instale as Dependências**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute o Script Principal**:
   ```bash
   python main.py
   ```

## 📊 Exemplo de Uso

O código inclui um exemplo de frases para testar o modelo treinado:

```python
exemplo_frases = [
    "I love this product!",
    "This is the worst experience I've ever had.",
    "It's okay, not bad.",
    "Absolutely fantastic!",
    "I hate it so much.",
    # ... mais frases
]

predicoes = best_model.predict(exemplo_frases)
for frase, sentimento in zip(exemplo_frases, predicoes):
    print(f'Frase: "{frase}"\nSentimento Predito: {sentimento}\n')
```

## 📚 Dependências

- `pandas`
- `numpy`
- `nltk`
- `scikit-learn`

## 🔗 Links Úteis

- [Documentação do Scikit-learn](https://scikit-learn.org/stable/documentation.html)
- [Documentação do NLTK](https://www.nltk.org/)
- [Documentação do Pandas](https://pandas.pydata.org/docs/)

## 🤝 Contribuições

Contribuições são bem-vindas! Se você encontrar um bug ou tiver uma sugestão de melhoria, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 📜 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Espero que você ache este repositório útil e interessante! Se tiver alguma dúvida ou sugestão, não hesite em entrar em contato. 😀

---
