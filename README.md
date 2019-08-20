# StackGAN-using-Tensorflow-and-Keras

### Main Reference
Tensorflow implementation for reproducing main results in the paper StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks by Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas.

* [StackGAN](https://github.com/hanzhanggit/StackGAN)

![alt text](https://raw.githubusercontent.com/hanzhanggit/StackGAN/master/examples/framework.jpg)

```
Run the code on Google Colab from the link Given Below
```

#### Data

Get the link to the dataset from the StackGAN link given above.

Download the dataset required and save that in your Google Drive so that it can be linked to Google Colab easily and fastly.
The process of linking Google Drive Data to Google Colab is give in the Code you just need to select the required dataset to be uploaded.


**Training**

  - Step 1: train Stage-I GAN (e.g., for 600 epochs)
  - Step 2: train Stage-II GAN (e.g., for another 600 epochs)

Stage-I GAN:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19P2wF8-JGfjzcfxtzDC7FsdKJhQmBKDG)

Stage-II GAN:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DvJD-NaS_aoeAFi_Hf9E6tKbevE76X5E)

Examples for birds (char-CNN-RNN embeddings), more on [youtube](https://youtu.be/93yaf_kE0Fg):
![](examples/bird1.jpg)
![](examples/bird2.jpg)
![](examples/bird4.jpg)
![](examples/bird3.jpg)


Examples for flowers (char-CNN-RNN embeddings), more on [youtube](https://youtu.be/SuRyL5vhCIM):
![](examples/flower1.jpg)
![](examples/flower2.jpg)
![](examples/flower3.jpg)
![](examples/flower4.jpg)




