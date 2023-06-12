# **D3APL: Aplicações em Ciência de Dados - IFSP Campinas**

**Professor:** Dr. Samuel Martins (Samuka)

**Alunos:**

* Gabrielly Baratela de Carvalho (CP3016331)
* Halisson Gomides de Souza (CP3016382)
* Hugo Martinelli Watanuki (CP3016692)


# **Celebrity Face Recognition Competition**

The objetive of this repository is to document and store the python code required to address a specific problem of computer vision: the recognition of the faces of celebrities contained in a public dataset (http://www.briancbecker.com/blog/research/pubfig83-lfw-dataset/).

This is an evolving project and this respository stores all the previous and current attempts to address the challenge. The latest and greatest notebook stored in this repository can be accessed here: https://github.com/HWatanuki/Projeto_D3APL/blob/main/resnet-flatten128-do-3-lr-005-samples80.ipynb

The is notebook is structured in four main sections that also represent the main steps adopted so far to address the problem:
1. Profiling the dataset
1. Defining a model and preprocessing the images
1. Training and fine-tuning the model
1. Final prediction and concluding remarks

The main approach currently being adopted to address the challenge involves addressing the class imbalance of the training dataset, preprocessing the images and the leveraging of a pre-trained face recognition model for transfer learning. The accuracy value obtained so far is approximatly 95%.

![image](https://github.com/HWatanuki/Projeto_D3APL/assets/50485300/2c0304a5-8a7e-4bad-9cd1-6dfa42d675a5)

