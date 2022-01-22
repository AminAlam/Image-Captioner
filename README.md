# Image-Captioner

### What is This?
It is a deep Neural network which uses CNNs, RNNs, and MLPs for captioning images. It was done for SUT DL course.

### Dependencies
You can intall all the dependencies using `pip install -r requirements.txt`.

### Architecture

I used resnet152 as CNN encoder and LSTMs as RNN decoder. You can see a schematic of the model in the image below.

![image 1](http://ee.sharif.edu/~amin/static/Deep/captioner_model.png)


### Training

The model was trained for 500 epochs on Tesal k80 GPU and [flickr8k](https://www.kaggle.com/adityajn105/flickr8k). The embedding layer weights were obtained from [Stanford glove.42B.300d](http://nlp.stanford.edu/data/glove.42B.300d.zip) (random value was used for the words which weren't in the glove).

### Loss and Accuracy

![Loss](http://ee.sharif.edu/~amin/static/Deep/captioner_loss.png)
![Accuracy](http://ee.sharif.edu/~amin/static/Deep/captioner_acc.png)


### Some Test Images

<!-- | ![image 1](http://ee.sharif.edu/~amin/static/Deep/captioner_1.png)  | ![image 2](http://ee.sharif.edu/~amin/static/Deep/captioner_2.png)|
| ------------- |-------------|
| ![image 3](http://ee.sharif.edu/~amin/static/Deep/captioner_3.png)  | ![image 4](http://ee.sharif.edu/~amin/static/Deep/captioner_4.png)| -->
