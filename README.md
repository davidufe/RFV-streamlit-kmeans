# RFV Streamlit — K-Means

Variante da aplicação de segmentação RFV, usando clusterização K-Means em vez de quartis fixos.

## Sobre

Em vez de classificar os clientes por quartis pré-definidos (A a D), esta versão aplica **K-Means** (com padronização via `StandardScaler`) sobre as variáveis de Recência, Frequência e Valor para agrupar os clientes de acordo com os grupos naturais encontrados nos dados, mantendo a mesma interface Streamlit e as recomendações de ação por segmento.

## Tecnologias

`Python` `Streamlit` `scikit-learn` (K-Means) `pandas`

## Estrutura do repositório

- `app_RFV_kmeans.py`
- `notebook_rfv_kmeans.ipynb`
- `requirements.txt`
- `dados_input 1.csv` — exemplo de base de entrada

## Como executar

```bash
pip install -r requirements.txt
streamlit run app_RFV_kmeans.py
```

## Autor

Davi Dutra Ferreira
[LinkedIn](https://www.linkedin.com/in/davidufe)
