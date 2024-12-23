The Generative Adversarial Neural Network (GAN), Fashionista, is built using TensorFlow and Python and leverages the Fashion MNIST dataset to generate realistic images of clothing items. This GAN consists of two key components: a generator and a discriminator. The generator is trained to produce synthetic images, while the discriminator learns to distinguish between real images from the dataset and those generated by the model. During training, the generator aims to "trick" the discriminator by improving the quality of its outputs, while the discriminator simultaneously becomes better at identifying fakes. This adversarial process drives both models to improve, resulting in the generation of increasingly convincing clothing images. Through this architecture, Fashionista demonstrates the power of GANs in creating new and realistic data.

Below are some photographs of the model input and output:

![input data](/images/input_data.png)

This is the set of input images from the fashion.mnist library from tensroflow.

![untrained output](/images/output_trainingless.png)

These are the results without training the two models.

![trained output](/images/output_trainingful.png)

The resultant output after training for around 2000 epochs.

![loss function](/images/loss_graph.png)

The graph tracking the loss function of the two models.
