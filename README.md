# virtual_bot_v2
A virtual assistant for restaurant trained on custom dataset using LSTM. 
The architecure is simple. 
First embed the input layers and pass them to LSTM. 
The output of LSTM gets fed to a time-distributed dense layer. 
This layer gets fed into a fully connected dense layer with classes_num as the number of nodes.

For interaction Google speech recognition for Nepali Language is used. 
