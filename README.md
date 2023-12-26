# Concrete_crack_detection_Image_classification

**Problem statement:** We have a collection of concrete images. We need to detect which concretes have cracks and which ones do not have cracks. 

We use the pre-trained RESNET18 model for this image classification problem: 

<img src="https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/80f17a30-562d-4a4b-a138-5d7012af28fc" width="300px">

We freeze the parameters of this RESNET18 model and modify the final output layer to predict the concrete crack detection problem. 

<img src="https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/adae3ead-f22e-4cfb-a024-5ea156d1a5b9" width="450px">


Model architecture: 

<img src="https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/bc1a2b55-6ea9-43e6-a970-b7a12cd2f5b1" width="400px">

1. Cross Entropy is used as the loss function.
2. Batch size is 100 and Adam optimizer is used. 

<img src="https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/11b59422-6220-4ade-8183-66cb0aa47ca6" width="450px">

1. Accuracy of the model is 99.51%.
2. Loss function convergence is plotted below. 

<img src="https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/3f416ca3-8dea-4ca6-bc79-1dcd00da9b7b6" width="350px">

**Below, I display 4 misclassified cases:** 

![image](https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/3e2ff3e4-af53-42af-b9b4-dea957aa0ddf)

![image](https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/5fd09370-2a2d-4585-92f4-0768be06c4dc)

![image](https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/ec04544f-1e13-47e4-90d8-d2afb3198494)

![image](https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/07c44eca-f6e1-4c03-be0f-81170de7fe18)

**Below, I plot some examples where the model correctly classified the concrete images as cracked.**

Classified successfully as cracked: 

![image](https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/05a92934-8ce0-4a99-a1cd-a61b53250177)

Classified successfully as cracked: 

![image](https://github.com/tsenguun0106/Concrete_crack_detection_Image_classification/assets/60633314/b96ca640-862f-4b27-849b-269b61222e43)

