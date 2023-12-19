Due to less computational resources i have trained the model on dataset by taking very less datasets at ones

Usually i took 2 person lungs data at one merged it and randomize it, which mimics the larger sample space

* Then in then two model file i have implemented two models
1) Small_encoder decoder model
2) Unet model 



* Then i got the best output when i used attention at positions level on then resnet level, i could have gotten more better results if i have had the time to use Unet and attention


FINAL INFERENCE:
my best model is in the file resnet_attention_final.ipynb file

to inference it we have to give numpy array as input 
(i used this format as the dataset was like this)