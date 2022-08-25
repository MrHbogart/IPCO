# IPCO EF7 Pollution prediction

This project is to predict pollution factors of EF7 CVVT engine based on data derive from censors such as engine speed,
torque, angle of camshaft and some other factors.

data needed to design and train this deep learning model provided by engine test group at Iran Khodro Engine R&D and Manufacturing Co.

based on these valuable data, we have designed a Deep Learning model with Keras on Tensorflow 

the model contains 6 dense hiddein layers with 256 node on each and a dropout of 0.2 on each layer
![alt text](https://github.com/MrHbogart/IPCO/blob/main/Readme%20files/model.png)

and activation function of all layers exept the output layer is ReLU
the model has been trained for 1024 epochs and batch-size of 64 and validation data of 0.2 portion of all data
the model history is showned in the next fig

![alt text](https://github.com/MrHbogart/IPCO/blob/main/Readme%20files/history.jpg)
