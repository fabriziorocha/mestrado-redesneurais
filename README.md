# Redes Neurais — trabalhos da disciplina

## Notebooks

| Notebook | Tarefa |
|---|---|
| [`01_mlp_numpy_vs_sklearn.ipynb`](01_mlp_numpy_vs_sklearn.ipynb) | MLP implementada do zero (NumPy), configurável em camadas, neurônios e ativações, comparada com o Scikit-Learn |
| [`02_cnn_mnist.ipynb`](02_cnn_mnist.ipynb) | Download e leitura dos arquivos originais do MNIST (formato IDX), pré-processamento e rede convolucional em PyTorch |

O notebook do MNIST baixa os dados automaticamente para `dados/mnist/` (pasta ignorada pelo git).

## Como executar

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
