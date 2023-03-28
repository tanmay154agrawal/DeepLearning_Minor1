# DeepLearning_Minor1
Tiny ImageNet is a subset of the ImageNet dataset in the famous ImageNet Large Scale Visual Recognition Challenge (ILSVRC).
The dataset contains 100,000 images of 200 classes (500 for each class) downsized to 64×64 colored images. Each class has 500 training images, 50 validation images, and 50 test images.

<img width="330" alt="image" src="https://user-images.githubusercontent.com/124059983/228312989-b3f723e7-5ee1-46d6-988f-df2d213c7a3a.png">

Make sure that you have set your Colab runtime to GPU. Once done, execute the following steps as part of the initial setup:
1.)Install and import the necessary Python libraries
2.)Define GPU support for PyTorch (i.e., use CUDA).
3.)Use GNU wget package to download from the official Stanford site

<img width="398" alt="image" src="https://user-images.githubusercontent.com/124059983/228313348-15e564a5-f065-4f93-a80e-e97ce13cbd32.png">

4.) Create DataLoaders for the image datasets


<img width="431" alt="image" src="https://user-images.githubusercontent.com/124059983/228313537-d7b8f9a6-d81d-4e78-9e07-2730f610d694.png">


5.) After that , do folder reorganization .


<img width="361" alt="image" src="https://user-images.githubusercontent.com/124059983/228313688-9b66c387-9c86-4538-b284-a7cc560c0f7a.png">

6.) Define image pre-processing transformations

7.) Define image pre-processing transformations

Here , Firstly a bigger Teacher model is trained and using knowledge distallation a smaller and faster student model is trained using pytorch

<img width="546" alt="image" src="https://user-images.githubusercontent.com/124059983/228314230-2e967e71-6d40-4bea-a261-a20f2adea5bf.png">

The Teacher was trained and saved for later training the student model . 
Results : 

Teacher Model : 

<img width="361" alt="image" src="https://user-images.githubusercontent.com/124059983/228314801-e5987875-3b63-4b52-8a32-f08fbfae3a8d.png">

Student Model :

<img width="307" alt="image" src="https://user-images.githubusercontent.com/124059983/228314907-2dd5f309-38b5-481a-b6d2-a9e02f7bd861.png">



