# Fine-Tuning de um modelo DistilBERT para análise de sentimentos em avaliações de filmes


Projeto para a disciplina de Processamento de Linguagem Natural realizando o **fine-tuning** do modelo **DistilBERT** para identificar se reviews do IMDb são **positivos** ou **negativos**.

## Visão-geral
- **Modelo**: DistilBertForSequenceClassification (2 classes, ~66 M parâmetros)  
- **Dados**: IMDb 50 k (balanceado)  
- **Principais libs**: `transformers`, `datasets`, `torch`, `scikit-learn`, `pandas`, `matplotlib`  
