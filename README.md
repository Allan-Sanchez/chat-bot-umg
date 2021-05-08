# Chat bot Para la UMG

## Descripscion

Este es un chat bot que responde a dudas acerca de la universidad Mariano Gálvez de Guatemala, actualmente solo responde a dudas sobre la carrera de Ingeniería de Sistemas, ya que este chat se desarrolló como un proyecto para el curso de Inteligencia Artificial

En este proyecto se utilizaron las librerías tales como: 
nltk
json
numpy
pytorch
tkinder

los pasos para instalacion
1. tener instalado git y clonar el repositoroio
 ``` 
 git clone https://github.com/Allan-Sanchez/chat-bot-umg.git
  ```
2. crear entorno virtual
```
conda create -n myenv
```
3. activar entorno virtual
```
source activate myenv
```
## paquetes a instalar
4. nltk
  ```
  pip install nltk
  ```
  
5. pytorch aqui depende del S.O ver la pagina oficial
  ```
  conda install pytorch torchvision torchaudio cpuonly -c pytorch
  ```
6. tkinder
  ```
  pip install tk
  ```
#Ejecutar en la terminar, esto para entrenar nuestro bot
```
python3 train.py 
```

#Ejecutar la interfas grafica
```
python3 app_ui.py 
```