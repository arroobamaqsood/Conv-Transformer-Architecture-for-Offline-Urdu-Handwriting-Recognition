# Conv-Transformer-Architecture-for-Offline-Urdu-Handwriting-Recognition

The repo contains a CNN block followed by a Transformer block (i.e. Conv-Transformer) for the task of Urdu handwriting recognition. A convolutional neural network (CNN) is used to extract the visual information from the image which is then fed to a full-transformer having three encoder and decoder layers stacked on top of each other. The encoded sequence is passed to a transformer decoder that digitizes the handwritten text. The model works in an auto-regressive fashion due to the presence of a transformer. 
