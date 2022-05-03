# NTU---Neural-Networks-and-Deep-Learning

**Image classification using ten categories from Materials in Context Database (MINC), 2,500 images per category.**

- CNN using MobileNetV2 and InceptionV3 pre-trained featurisers. 
- Hyperparameters tuned on final layers, including number of neurons, dropout and optimiser. 
- TensorBoard to visualise experiment results.
- Tested fine-tuning by unfreezing final layers of featuriser. 
- Best accuracy of 0.8594 obtained using 96 neurons in hidden layer, 96 neurons in hidden layer with 0.10 dropout probability, SGD optimiser, unfreeze final layers in featuriser. 
- Files include Python code, PDF report, presentation slides. 
