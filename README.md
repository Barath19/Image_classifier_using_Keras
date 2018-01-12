# Image_classifier_using_Keras
Image Classification using Convolutional Neural Nets and Keras. This classifier uses LeNet-5, a pioneering 7-level convolutional network by LeCun et al in 1998 that classifies digits.  

Requirements: Python 3.5 ,Keras 2.0.2 , Tensorflow 1.2.1 , OpenCV 3.3, numpy 1.11.0   

# How to:    
 ### Train your own model:     
     $ python train_network.py --dataset images --model Bharath_Kumar.model   
         
 ### Test your own model:    
     python test_network.py --model Bharath_Kumar.model --image images/examples/bk19.jpg    
     
  ### Add Your own Dataset:    
     Add your training images in  images/<Your Label>/

## Contents /Scripts of Barath Classifier :):  
  ### -train_network.py :    
        To train the  model.    
  ### -test_network.py:    
        To train the  model.    
  ### -Bharath_Kumar.model :   
        Model generated during thhe training.    
  ### - data.zip :    
        Contains Images for Training. Use your owm data set here.    
  ### -BK_lenet.zip :    
        LeNet Architecture.      

# About The Model:       
![alt tag](https://github.com/Barath19/Image_classifier_using_Keras/blob/master/lenet_architecture.png)      

Trained using Backpropogation algorithm with stochastic gradint descent. This is a Binary Classifier.   
## Accuracies after 25 epochs:  
### For classification based model:    
    -Train acc: 96.4665%    
    -Test acc : 88.5039%       
