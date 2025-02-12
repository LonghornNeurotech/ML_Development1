# ML DEV 1 MODELS

This is a folder of the models researched and developed by ML Team 1, trained on LHNT offline data. Below are the models and their input shapes

1. ATC_Net - 16 channels x 1750 time points
2. PCNN - 16 channels x 125 time points


# HOW TO USE

1. download the pth file
2. download the notebook for debugging
3. use torch.load("pth file") to load a model - if you just have the state dict, refer to the notebook for the actual model architecture
4. shape your inputs to be compatible with the model's inputs (generally just modify the input length (time steps))
5. use model.predict(input sample) to make a binary prediction

