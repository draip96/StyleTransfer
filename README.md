# Cropless Style Transfer

Complex Convolutional Neural Network model that applies the artistic style from one image to another image. The content image receives the art style from the style image, while still preserving it's content. This model was adjusted from the pytorch tutorial to allow for images of differing sizes. By adjusting the gram matrix function, our model can transfer styles from images of different resolutions, while preserving the aspect ratios. Additionally, the training procedure was modified to capture images throughout the style transfer process for greater ability to choose the amount of style to be transferred and content to be preserved.

<img src="https://user-images.githubusercontent.com/11250972/211645708-da44841a-bf25-4f82-919e-de85368b6121.jpg" width=50% height=50%>

![comp](https://user-images.githubusercontent.com/11250972/211645750-46fccdfe-7b88-4061-a2b7-6a999bc5a8ed.jpg)
![dog1](https://user-images.githubusercontent.com/11250972/211646222-b3d987e8-2911-4119-9648-db6f7dbfc342.png)



![car](https://user-images.githubusercontent.com/11250972/211645843-019dfdca-1afc-4afb-9413-c5b486819611.jpg)
![shapes](https://user-images.githubusercontent.com/11250972/211646149-b9b05420-8fcc-4222-b363-a5ec89841d88.jpeg)
![car1](https://user-images.githubusercontent.com/11250972/211646258-5263aad3-0dc5-4fb6-8ca9-328f1fe42a74.png)
