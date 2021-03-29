# sudo docker run --gpus all -it --rm tensorflow/tensorflow:latest-gpu bash -c "pip install keras"
FROM tensorflow/tensorflow:latest-gpu 

MAINTAINER romank.d.kim@gmail.com

RUN apt-get -y update

RUN pip install -q transformers torch keras sklearn pandas numpy matplotlib jupyter 
