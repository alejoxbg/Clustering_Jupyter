# Clustering_Jupyter

_Se recomienda leer el reporte final donde se explica cuales variables se pueden modificar para cambiar la ruta donde se tienen los datos binarios y también cuales parámetros se pueden ajustar para cambiar el rendimiento de los algoritmos implementados._

## Preview
Segmentación del suelo con RANSAC:
![planeRANSACsegmentation](https://user-images.githubusercontent.com/55366335/96387537-67c27400-1168-11eb-8265-4cdff214bdf6.png)
Clustering con Kmeans (parámetros modificables):
![kmeans_clustering](https://user-images.githubusercontent.com/55366335/96387596-e9b29d00-1168-11eb-995c-6437453a690c.png)

## Comenzando 🚀

### Pre-requisitos 📋
  El siguiente código fue probado en Jupyter Lab con python3.
  
  Se recomienda realizar un entorno virtual para hacer las instalaciones de librerías, así:
  
  En una terminal:
  
  python3 -m venv --system-site-packages ./<nombre_del_entorno>
 
  
  Ejemplo:
```
python3 -m venv --system-site-packages ./kittiv
 ```  
   
   Para iniciar el entorno virtual:
   
```
source kittiv/bin/activate
 ```  
   
   Para cerrar el entorno virtual:
   
 ```
deactivate
 ```  
        
  (Las instalaciones de las librerías se hicieron por medio de pip)
 
### Instalar librerías especiales 🔧

Con el entorno virtual **activado**, ejecutar:
```
pip install jupyterlab
pip install open3d-python
pip install hdbscan
```

Para más documentación sobre Open3D: http://www.open3d.org/docs/release/index.html

Para más documentación sobre HDBSCAN: https://hdbscan.readthedocs.io/en/latest/index.html

Para más documentación sobre algoritmos de clustering con scikit learn: https://scikit-learn.org/stable/modules/clustering.html

## Abrir archivo .ipynb en Jupyter⚙️

Se usa el siguiente comando para ejecutar Jupyter Lab (con el entorno virtual **activado**):
```
jupyter lab
```

(El archivo .ipynb puede correr en otro entorno diferente al de Jupyter Lab, pero se presentan problemas en entornos como el de Google Colab porque no permite abrir las ventanas emergentes de Open3D).
