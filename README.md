# TB-classification
Tuberculosis classification

Classifying the tuberculosis in X-ray image
It is simple binary classification, but I use Vision transformer to achieve this task.

Through ViT, the original ViT has worse acc compare to ResNet50.
Maybe the reason why ViT get lower acc is that there are only 4200 dataset and there are large difference in number of samples between normal and TB dataset.

However, convolution-transformer hybrid network get better acheive to the task.
T2T(Token to Token) get similar result to ResNet,
and CMT(Convolution Meet Transformer) model get high acc than ResNet.

For all transformer model that I used, I modificate model's depth and dimension so that the number of parameters are much smaller than ResNet.

To sum up, 
I get similar and better acheivement than ResNet through variations of transformer with using fewer parameters.
