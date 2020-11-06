# NER
This is a simple named entity recognition system using LSTM architecture. This model is developed using Pytorch and I use notebook to write the code so I can
evaluate and trace the inputs, step by step. 

The code is pretty strightforward. I first load the train and test data, preprocess them and then using pytorch.Dataset, I create a class to generate the batches
for the model. Then using torch.nn, I defined my network and its parameters. The rest is training, evaluating and at the end the prediction function. 

As you can see in the notebook, I only trained the model for 4 epochs. It is not enough at all, and even though the accuracy is good, but it is not enough yet. The reason the I did not run it any longer is becasue I trained it on my laptop and to fully train the model it requiers a GPU or a computer that can run this model on CPU for a longer time. 

If you want to send the model on GPU, you should make some modification to the code. Change the pytorch device and send the model and inputs to the gpu device. 
