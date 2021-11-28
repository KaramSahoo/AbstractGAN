
# AbsractGAN

Creating new abstract art using a Generative Adversarial Network.




## What are GANS?

Generative Adversarial Networks, or GANs for short, are an approach to generative modeling using deep learning methods, such as convolutional neural networks.

Generative modeling is an unsupervised learning task in machine learning that involves automatically discovering and learning the regularities or patterns in input data in such a way that the model can be used to generate or output new examples that plausibly could have been drawn from the original dataset.

GANs are a clever way of training a generative model by framing the problem as a supervised learning problem with two sub-models: the generator model that we train to generate new examples, and the discriminator model that tries to classify examples as either real (from the domain) or fake (generated). The two models are trained together in a zero-sum game, adversarial, until the discriminator model is fooled about half the time, meaning the generator model is generating plausible examples.


## Why abstract art?
## Demo

Insert gif or link to demo


## Dataset

The dataset is available in Kaggle. Click [here](https://www.kaggle.com/bryanb/abstract-art-gallery) to get the dataset. The images are scrapped from the web hence require additinal resizing and reshaping before feeding to the GAN network.

## Methodology
## Results
## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

