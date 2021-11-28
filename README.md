  Basically what my project does:

![image](https://user-images.githubusercontent.com/38115399/143766076-76a2d2a0-2251-43da-a3bf-a9d6fbd931cd.png)



# Purpose of this repository
This is the repository for storing data and code files from the final semester of my Bachelor's degree for my Capstone Project
Since the pickle files for the data are too large to be uploaded to github, we have uploaded them to Google Drive. 
<br></br>You can find all of the data here: https://drive.google.com/drive/folders/1dXxqYkei1ptmNacIFFfNIB8n7JLXwLRM?usp=sharing
<br></br>The code is available in the form of .ipynb file pre-run with output images available.
# What I've done in this project
Here's a brief video explaining what I've done in this project:

https://user-images.githubusercontent.com/38115399/143388183-35914e1e-ee8f-4ce1-8dbe-44b30c712b2f.mp4



In this project, I aimed to accomplish the following objectives, listed and completed in
sequence:<br></br>
● To load a VGG16 network without its top, pre-trained on ImageNet<br></br>
● To load the FERG-2D Dataset and pre-process it<br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ Removal of transparency (4th channel)<br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ Crop out image faces<br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ Convert to grayscale (colour is irrelevant to expression, simply adds noise)<br></br>
● Obtain bottleneck features from FERG with VGG<br></br>
● Use our Fully Connected Network and pre-train on FERG<br></br>
● Load Extended Cohn Kanade dataset and pre-process it<br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ Resize<br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ Add redundant <br></br>
● Obtain effective data for cartoonization<br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ Flickr HQ Dataset (FFHQ)<br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ Anime Names and Images Dataset<br></br>
● Obtain bottleneck CGAN with Shinkai training<br></br>
● Train a proper CGAN using FFHQ and Anime Images data<br></br>
● Effectively use the network to cartoonize CK+ dataset<br></br>
● Successfully apply Image Augmentation to CK+ dataset<br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;○ Lateral Flipping of the images to effectively double the training data<br></br>
● Create 10 folds of data, stratified by emotion class label<br></br>
● Train models for 10 epochs each at every 10th percentage between 10 and 100, and
track results at each step<br></br>
● Plot and analyse the resultant data and obtain inferences<br></br>
● Implement a live webcam function to capture images, cartoonize them and detect
emotions in real-time<br></br>
# Quick Look at the Results
Here's a video briefly demonstrating the results:

https://user-images.githubusercontent.com/38115399/143386536-3dc07616-7cf6-4598-a863-e9d2748a842b.mp4


<br></br>
The following images are some further examples of how my project works
<br></br>
![surprise](https://user-images.githubusercontent.com/38115399/143385710-2957164e-724b-4d9f-abb7-14cf65089ad9.JPG)
<br></br>
![anger](https://user-images.githubusercontent.com/38115399/143385663-4b62cf94-270c-4300-9557-552b2287abf6.JPG)
<br></br>
![disgust](https://user-images.githubusercontent.com/38115399/143385684-bcef73e3-e7e7-43ad-a231-c92d6e6a1b00.JPG)
<br></br>
![fear](https://user-images.githubusercontent.com/38115399/143385689-d0390b8e-c546-43c9-acc2-a0f0f27d2bb6.JPG)
<br></br>
![joy](https://user-images.githubusercontent.com/38115399/143385700-842b4e55-a201-47b1-bd80-00500fd68a8f.JPG)
<br></br>
![sadness](https://user-images.githubusercontent.com/38115399/143385707-b5ed8163-7994-45e8-b306-b1ac38d9ae4c.JPG)
<br></br>

