#### **A discussion on Autoencoders**

An **Autoencoder** is an **unsupervised** Neural Network. It learns from *data without labels*. It looks at the data, our **input**, and tries to learn and create a meaningful, condensed representation of that data, which is the **code** in the middle, and from the **code**, it will try to ***reconstruct*** the input, albeit with some **amount of error**, called the ***reconstruction error***.

Inside the [**Autoencoders**](./Autoencoders.ipynb), we start by discussing **Undercomplete Autoencoders**, which is the basic implementation of Autoencoders and useful for dimensionality reduction.

Next, we will understand about **Variational Autoencoders**, its architecture and how it is useful for Data Generation. Like how we can produce variations of images, and how we can address class imbalance in order to improve training of a machine learning model or a neural network.

(Here is a repository for Autoencoders made by the author to document his learnings regarding the topic. The pictures used in the notebook are not of his own and are just used to supplement the visual understanding necessary for learning. One valuable resource especially for the Reparameterization Trick is from this video https://www.youtube.com/watch?v=vy8q-WnHa9A&list=LL&index=58 made by [ML Explained](https://www.youtube.com/@raneisenberg2155))

This repository is available to everyone who wants to read about Autoencoders.