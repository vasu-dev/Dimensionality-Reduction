## Dimensionality Reduction

A comparison b/w autoencoders and pca for dimensionality reduction.

### Dataset : MNIST

link: https://www.kaggle.com/c/digit-recognizer/data

Used mnist/train.csv : Training on first 30,000 datapoints,
                       Validation on rest 12000 datapoints.
        

### CASES
  
  #####  1) From 784 to 32 dimensions.
          
          Results : a) PCA : Training Accuracy : 80%
                             Validation Accuracy : 91%
                    
                    b) Autoencoders : Training Accuracy : 61%
                                      Validation Accuracy : 84%
                                      
  #####  2) From 784 to 2 dimensions.
         
         Results : a) PCA : Training Accuracy : 43%
                             Validation Accuracy : 47%
                    
                    b) Autoencoders : Training Accuracy : 55%
                                      Validation Accuracy : 65%
  
