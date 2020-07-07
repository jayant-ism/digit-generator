In this project a Machine  Learning  model that converts any noise(usually a  distorted image ) into  a handwritten digit was designed  using DCGANS.
Tensorflow is used to design this model. This model can be used to increase the quality of images containing handwritten digits and thus  can find an application in converting old handwritten records into digital format.
The project consist of two models - a generator and an image classifier.
MNIST dataset of images of handwritten digits was used to train the classifier.
During training a random image is fed into the generator model and the output is fed to the classifier, the classifier is then trained to identify all the images from the dataset as the handwritten digits, and non-handwritten digits to that of  the image generated from the generator. The generator is then trained to fool the classifier.

After training the model it was able to enhance the quality distorted images of handwritten digits. Moreover it was also able to generate new images of the same.
This technology can be used to train the models for whom a large quantity of dataset is unavailable, usually we can train a DCGAN for that particular  dataset and by feeding it noise new dataset will be generated which can be further used in training other models.
  
