# Dog breed identification

Here we train a deep learning algorythm to identify the breed of a dog from a photography. We use different methods : VGG16 from scratch, VGG16 transfered and EfficientNetB7 transfered.

As such CNN constitute state of the art methods in image recognition it is an interesting choice of programs. We remind here that CNNs are hegemonic in this domain, over other machine learning technique, thanks to their specific architecture allowing them to reduce parameters number through convolutional layers and therefore schrinking computation time and avoiding overfitting.     

Training was done with a google collab GPU (40gb vram)

The original data is the Stanford Dogs dataset (http://vision.stanford.edu/aditya86/ImageNetDogs/)

We also implemented a variant of training made to examine the impact of using lion algorithm.
