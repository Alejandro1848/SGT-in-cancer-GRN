# SGT-in-cancer-GRN

 
#### PlotGraphWithLabeledVertices: 
Con este script se puede visualizar el grafo asociado a la matriz de adyacencia calculada a partir del data set output de ARACNe, con etiquetas de los genes para cada vértice.
 
#### AlgebraicConnectivityAnalysis_UNS y AlgebraicConnectivityAnalysis_UNT: 

Estos scripts sirven para calcular  <img src="https://render.githubusercontent.com/render/math?math=a(G)"> y <img src="https://render.githubusercontent.com/render/math?math=\delta(G)">, conectividad algebraica y menor grado respectivamente del grafo <img src="https://render.githubusercontent.com/render/math?math=G">, asociado a la matriz de adyacencia.


#### EigVecCentAnalysisUNS.ipynb y EigVecCentAnalysisUNT.ipynb: 
Estos scripts sirven para calcular la centralidad del vector propio. Se extraen los valores de la diagonal de la matriz
de grado y se guarda en una lista, y se calcula el producto entre la matriz de adyacencia del grafo en cuestion por esta lista , obteniendose un nuevo array. Así, se reasigna a cada vértice la suma de los valores de sus vértices vecinos.
