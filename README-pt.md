# vanilla-knn

[![PyPI version](https://badge.fury.io/py/vanilla-knn.svg)](https://badge.fury.io/py/vanilla-knn)

Uma implementação simples do algoritmo k-Nearest Neighbors (KNN) com distância euclidiana sem utilização de bibliotecas externas.

## Instalação

Você pode instalar o `vanilla-knn` usando o pip:

```bash
pip install vanilla-knn
```

## Uso

```bash
from vanilla_knn.knn import k_neighbors_classifier

# Criar um modelo KNN
modelo = k_neighbors_classifier(n_neighbors=3)

# Treinar o modelo
X_train = [...]  # Seus dados de treinamento
y_train = [...]  # Suas etiquetas de treinamento
modelo.fit(X_train, y_train)

# Fazer previsões
X_test = [...]  # Seus dados de teste
y_pred = modelo.predict(X_test)

# Imprimir as previsões
print("Previsões:", y_pred)
```

## Contribuições

Se você quiser contribuir para o desenvolvimento deste projeto, sinta-se à vontade para enviar pull requests ou relatar problemas.