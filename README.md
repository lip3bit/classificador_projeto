# classificador_projeto

Prova de Machine Learning: implementação e comparação de dois classificadores supervisionados.

- **Base:** [Forest Covertype](https://archive.ics.uci.edu/ml/datasets/Covertype) (581.012 amostras, 54 features, 7 classes)
- **Métodos:** Regressão Logística e Random Forest
- **Notebook:** [`classificador.ipynb`](classificador.ipynb), já executado

## Como reproduzir

```bash
pip install -r requirements.txt
jupyter notebook classificador.ipynb
```

A base é baixada automaticamente pelo `sklearn.datasets.fetch_covtype` (cerca de 11 MB) na primeira execução. A execução completa leva por volta de 45 minutos em um computador com 16 núcleos e precisa de uns 8 GB de RAM livres.
