## LeNet-5 model

A simple LeNet-5 model trained by keras. The development environment is as follows.

```
Python 3.7.3
Tensorflow 1.13.1
Keras 2.2.4
```

You can easily use this trained model by using the following script

```python
model = load_model('lenet_model.h5')
predict_out = model.predict(input)
```