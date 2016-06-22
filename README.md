### Install

For Python 2.x and Python 3.x respectively:

```python
pip install classification_models


```

In the end, you can import the sub-package...

```python
from classification_models import classification_models

```
### Description

```python
- Este algoritmo tiene como entrada un dataframe, su target y el tamaño de train_set
- Realiza cinco modelos (SVM,RANDOM FOREST, DECISION TREE, LOGISTIC REGRESION, LDA) y clasifica cada uno de ellos basandose en su gini.
- Realiza la selección de variables para cada modelo. Para SVM,LOGIST REGRESSION y LDA utiliza el algoritmo de seleccion genética para ello. Para decision tree y random forest utiliza la seleccion  de variables de sklearn para llevar a cabo la seleccion de variables. Dibujo arboles con diferentes profundidades y almacena el mejor valor como representativo para decision tree. Lo mismo para random forest.


```
