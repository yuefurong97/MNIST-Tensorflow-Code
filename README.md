## MNIST-Tensorflow 99.xx%

**I write a Tensorflow code for Classification of MNIST Data.**

You can get the results with following command:
```
python main.py --num_epoch 150
```

**This code has following features**

1. Data Augmentation is used (Training data: 50,000 -> 250,000)

2. 3x3 Conv with He_initializer, Strided Conv, batch_norm with decay rate 0.9, Max_Pooling are used

3. Activation Function is tf.nn.leaky_relu

4. Global Average Pooling is used instead of MLP

5. L2 Regularization Loss, Learning Rate Decay, Adam Optimization with beta1 = 0.5 are used

6. It Contains Codes for Tensorboard, Save, Restore 
