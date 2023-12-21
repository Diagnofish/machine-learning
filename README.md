# Machine Learning Repository for Diagnofish

# Dataset

<img src="https://github.com/Diagnofish/machine-learning/assets/108395348/d5c158c9-e65d-4fdb-b152-099bf2feb0f0" alt="fish_image" width="700" height="auto">


The dataset we use is from [Kaggle: Freshwater Fish Disease Aquaculture in south asia](https://www.kaggle.com/datasets/subirbiswas19/freshwater-fish-disease-aquaculture-in-south-asia/data) 
<p align='justify'>
The dataset consist of images categorized into seven classes, with six classes corresponding to different fish diseases and one class representing healthy fish. The classes include:
  
1. Bacterial diseases - Aeromoniasis
2. Bacterial gill disease 
3. Bacterial Red disease 
4. Fungal diseases 
5. Healthy Fish 
6. Parasitic diseases 
7. Viral diseases White tail disease

The downloaded dataset is available in a compressed .zip format within the **dataset folder** of this repository.

# Model
<p align='justify'>
We developed a multiclass classification model by leveraging the MobileNet architecture as a pretrained model from TensorFlow Hub. Setting the trainable parameter to True, we fine-tuned the model and enhanced its performance by adding two additional dense and dropout layers. The model get 86% accuracy on the validaton data. The model's structure is shown in the image below:
<br><br>
<img src="https://github.com/Diagnofish/machine-learning/assets/108395348/1e752982-151c-4651-8e89-8ff1e91b4c0c" alt="fish_image" width="auto" height="600">

Access the pre-trained model we used via this [link](https://www.kaggle.com/models/google/mobilenet-v2/frameworks/TensorFlow2/variations/140-224-feature-vector/versions/2). 

<p align='justify'>

To see how we built the model, take a look at the jupyter notebook file in the **notebook folder** in this repository. To obtain the model in h5 format, open the model.md file and click "here", you will be directed to Google Drive, where the model is stored.



