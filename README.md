# Acerca del trabajo

En este trabajo buscamos comprender mejor los algoritmos de clasficación Knn y Árobles de decisión. Para esto trabajamos con Fashion-MNIST, un dataset con imagenes 28x28 de prendas clasificadas según 10 clases. 

Trabajo académico realizado durante 2025 para la materia Laboratorio de datos de la Licenciatura en Ciencia de Datos de la Universidad de Buenos Aires (UBA). Integrantes del grupo: Guillermo de La Vega, Francisco Anllo y Matías Naddeo


---

## ¿Cómo ejecutar el código?

1. Necesitás tener Python 3 instalado.
2. Al principio se deben poder importar las siguientes librerías (en caso de no poder, debes instalar las dependencias):
```bash
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import duckdb as dd
from sklearn.datasets import load_iris
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn import tree
from sklearn.neighbors import KNeighborsClassifier
from sklearn.model_selection import train_test_split,KFold
from sklearn import metrics
import random
from sklearn.tree import DecisionTreeClassifier
```
3. En la terminal debes correr:

```bash
python main.py
```
