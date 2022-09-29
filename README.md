# Cotton-Plant-Disease-Detection
### --------------------Algorithms I used:-----------------------
I used Convolutional Neural Networks (CNN).                                                   
Architecture: ResNet 50 ,VGG 16 and custom.

#### Custom Network: 
1.Convolutional Layer - 2                             
Max Pooling layer - 2                               
Flatten and Dense layer                             
Input size: 64*64                

2. Convolutional Layer - 4                   
Max Pooling layer - 3   
Flatten and Dense layer                         
Input size: 224*224          

### ----------------Result and Discussion------------------------
#### Architecture Accuracy:                       
 VGG16      96%              
 ResNet50  65%                               
 Custom    97%           

#### Validation Accuracy:
VGG16      96%              
 ResNet50  76%                               
 Custom    91%    
 
 #### Loss:
 VGG16      11%              
 ResNet50                                  
 Custom     7%    
 
Designed architecture shows highest accuracy 97% besides VGG16 shows 96%
Accuracy which is pretty good. On the other hand, ResNet50 has given lower 
accuracy may be the reason is small dataset.

![cotton plant1](https://user-images.githubusercontent.com/68694418/192964323-f4207fe5-e607-476b-998c-f8039e63842e.png)

Figure 1 shows that, train accuracy increased 
gradually.Test accuracy also increased gradually 
but the curve is not smooth. 


