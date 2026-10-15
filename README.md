# Redes Neurais — trabalhos da disciplina

## Notebooks

| Notebook | Tarefa |
|---|---|
| [`01_mlp_numpy_vs_sklearn.ipynb`](01_mlp_numpy_vs_sklearn.ipynb) | MLP implementada do zero (NumPy), configurável em camadas, neurônios e ativações, comparada com o Scikit-Learn |
| [`02_cnn_mnist.ipynb`](02_cnn_mnist.ipynb) | Download e leitura dos arquivos originais do MNIST (formato IDX), pré-processamento e rede convolucional em PyTorch |
| [`03_forecasting_carga_ons.ipynb`](03_forecasting_carga_ons.ipynb) | Previsão da carga horária de energia do subsistema Sudeste/Centro-Oeste (dados abertos do ONS) 24 h à frente com Keras: baselines ingênuos, rede densa, Conv1D, LSTM, LSTM com dropout e LSTM bidirecional |
| [`04_sentimento_imdb_transformers.ipynb`](04_sentimento_imdb_transformers.ipynb) | Análise de sentimento da base IMDb (Stanford) com a `pipeline` do Hugging Face Transformers, incluindo as etapas internas da pipeline |

Os notebooks baixam os dados automaticamente para `dados/` (pasta ignorada pelo git). O notebook do IMDb usa GPU se o PyTorch com CUDA estiver instalado; na CPU, a classificação das 25.000 resenhas de teste leva cerca de 2 horas por modelo.

## Como executar

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
