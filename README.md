## DeepLearningWithPytorch-ZeroToGANs

##Cats and Dogs Classification using Feed Forward and Convolutional Neural Networks in PyTorch

--- 


---


<img src='https://media.giphy.com/media/Rdx8SHjHhiVUI/giphy.gif'
style="width:1000px; float: left; margin: 0 0px 0px 0px;"></img> 


---





---



### This project will be running and  comparing between the feed forward neural network and ResNet architectures.

- Train and validation datasets will both be taken from the training_set and test_set respectively 
- Same batch size will be used for both models which is = 16
- output size is 2
- dataset used is normalized and augmented

**[view Course Certificate](https://jovian.com/certificate/MFQTGOJVGI)**

example source code and Pytorch images:
import matplotlib
import matplotlib.pyplot as plt
%matplotlib inline

matplotlib.rcParams['figure.facecolor'] = '#ffffff'


def show_example(img, label):
    print('Label: ', dataset.classes[label], "("+str(label)+")")
    plt.imshow(img.permute(1, 2, 0))
    print(img.shape)

- Visualize the same image (dataset and train_ds) first with no transforms then with different transforms definition
  show_example(*dataset_raw[9]) #image before normalization
<img width="705" alt="pytorch image" src="https://github.com/dajo09/DeepLearningWithPytorch-ZeroToGANs/assets/33592524/2e1af430-7369-4f28-a80e-29a9ea562878">



