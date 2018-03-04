## Caption Generation using VGG16 and LSTM
MD Muhaimin Rahman
contact: sezan92[at]gmail[dot]com

In this project, I have tried to work on Caption generation of Images of Flickr_8k dataset. I took extensive help from Jason Brownlee's Blog [article](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/) on the same dataset. But I thought some codeblocks were unnecessarily complex . So I changed them for my project. The main architecture is mainly taken from Googles [paper](https://arxiv.org/abs/1411.4555),

Some Examples:
![Caption1](Caption0.jpg)
![Caption2](Caption1.jpg)
![Caption3](Caption2.jpg)
![Caption8](Caption7.jpg)
![Caption13](Caption12.jpg)

### Dataset
I have used Flickr8k dataset, which I cannot redistribute. You have to fillup this [form](https://forms.illinois.edu/sec/1713398) and they will give you the dataset. You have to keep the folders ```Flicker8k_Dataset``` and ```Flickr_Text``` inside the ```dataset``` folder.
 
### Further Improvement:
Till now, I have used features extracted from the VGG16 Model and trained on them . I think fully trainable model should improve the results which I am looking forward to work in future , God Willing.
