# SGT-in-cancer-GRN

 
#### PlotGraphWithLabeledVertices: 
Con este script se puede visualizar el grafo asociado a la matriz de adyacencia calculada a partir del data set output de ARACNe, con etiquetas de los genes para cada vértice.
 
#### AlgebraicConnectivityAnalysis_UNS y AlgebraicConnectivityAnalysis_UNT: 

Estos scripts sirven para calcular  <img src="https://render.githubusercontent.com/render/math?math=a(G)"> y <img src="https://render.githubusercontent.com/render/math?math=\delta(G)">, conectividad algebraica y menor grado respectivamente del grafo <img src="https://render.githubusercontent.com/render/math?math=G">, asociado a la matriz de adyacencia.


#### EigVecCentAnalysisUNS y EigVecCentAnalysisUNT: 
Estos scripts sirven para calcular la centralidad del vector propio. Se extraen los valores de la diagonal de la matriz
de grado y se guarda en una lista, y se calcula el producto entre la matriz de adyacencia del grafo en cuestion por esta lista , obteniendose un nuevo array. Así, se reasigna a cada vértice la suma de los valores de sus vértices vecinos.


#### SignlessLapMatAnalysys_UNS_3.0 y SignlessLapMatAnalysys_UNS:
Estos scripts sirven para calcular coeficientes de polinomio característico para diferentes tamaños de sub-matriz de adyacencia, o lo que es lo mismo conjuntos más pequeños del data set original sobre el que se hacen todos los cálculos, cuyo header se pone al inicio del script con tamaño aproximado de <img src="https://render.githubusercontent.com/render/math?math=16000\times16000">
