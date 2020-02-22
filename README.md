# styleTransferOnImageUsingCNN
We use a pre-trained model, VGGNet in our case for the python implementation of style transfer.

We will see the python implementation of style transfer. For the demonstration, let’s take the image of a rabbit as the content image and  splash of colours as the style image. You can, of course, use any set of images for your notebook.  

  
In the case of transfer learning, we use a pre-trained model, VGGNet in our case, and remove its last fully connected layer since our task is not to classify the image. Here, we use the pre-trained weights of the model to update the candidate image instead of updating the model weights. Since there are no prebuilt functions to train these type of networks in Keras,  you will see that we will use lots of custom functions.  

## Conclusion:  
We learnt how to load the VGG-19 model, preprocess the data, and then define the placeholder for the generated image.  Next, we will define the loss functions, define the layer from which we want to extract the features, define custom keras function and train the pixels of the generated image.   
  
We have trained for 10 iterations. You can see the difference between the generated image at iteration-0 and iteration-5 and iteration-9. As the number of iterations increases, there is a clear effect of the style image on the generated image.  



