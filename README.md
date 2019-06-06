# deep-learning-hands-on

Projetos de Deep Learning que eu utilizo durante as aulas.

### Instruções para instalação de pré-requisitos:

Requisitos principais:
- Ubuntu16.04 or Windows10  
- python3.6.2 

1. Instalar o [GitHub para Windows](https://desktop.github.com/)
2. Instalar o [Anaconda para Windows](https://docs.anaconda.com/anaconda/install/windows/)

3. Abrir o Git Shell e executar o seguinte comando:
```
git clone git@github.com:felipheggaliza/keras-facenet.git
```
4. Faça o download do arquivo facenet_keras.h5 através do [link](https://drive.google.com/open?id=1PZ_6Zsy1Vb0s0JmjEmVd8FS99zoMCiN1) 

5. Coloque o arquivo facenet_keras.h5 dentro do diretório: <path_to_repo>/keras-facenet/model

6. Abrir o Anaconda Prompt e executar os seguintes comandos:
```
conda create -n facenet python=3
conda activate facenet
pip install numpy scipy matplotlib scikit-learn imageio scikit-image jupyter
pip install opencv-contrib-python
pip install tensorflow
pip install keras
pip install xgboost
```
7. Inicie o jupyter notebook dentro do diretório keras-facenet
```
jupyter notebook
```
8. Abra o arquivo notebook/03-Facenet.ipynb

Créditos:

https://github.com/nyoki-mtl/keras-facenet

https://github.com/udacity/deep-learning-v2-pytorch

