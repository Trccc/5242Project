# 5242Project

Final Project for 5242 Advanced Machine Learning  

This is the github for the whole project results.

## Enviroment

The majority of work is done on the Google Cloud Platform by running scripts on Nvidia Tesla P100 GPU due to the limitation of notebooks.

## Dependency

Tensorflow 2.0

## Members

Chirong Zhang cz2533  
Yunxiao Zhao yz3380    
Zhichao Liu zl2686  
Yusang Mao ym2694  

## Tasks

1. Implement Inception score

2. Try different architectures

3. Try GAN on SVHN data

4. Implement different kinds of GAN  

   - DCGAN  
   - FCCGAN  
   - WGAN   
     - clip wgan-clip  
     - gradient penalty wgan-gp  

   - Spectrual Normalization   

## Results

SVHN  
![svhn](SVHN.gif)

MNIST  
![mnist](mnist.gif)

## To Run

To run a certain model  
Modify the global variables in config.py then
```
python main.py 
```

## Reference

[Inception Score](https://arxiv.org/abs/1606.03498)  

[FCCGAN](https://arxiv.org/abs/1905.02417)  

[WGAN](https://arxiv.org/abs/1701.07875)

[WGAN-gp](https://arxiv.org/abs/1704.00028)

[Spectral Normalization](https://arxiv.org/abs/1802.05957)

## Acknowledge

The main training process code is modified from [DCGAN tensorflow tutorial](https://www.tensorflow.org/tutorials/generative/dcgan).
