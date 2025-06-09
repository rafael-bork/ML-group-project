# Machine Learning Group Project Proposal  

## Monitoring Iberian Plant Diversity through a Collecting-based Mobile Application 

### Image Segmentation and Classification problem 

### Group Members:   

- Diogo Gomes - nº26843 
- Janice Rodrigues - nº 25902 
- Rafael Oliveira - nº 26606 

In this project we intent to set up the groundworks for the development on a mobile application that allows the user to collect vegetation species in augmented reality. The backbone will be a model that allows for the segmentation and classification of user-taken images, that allows them to unlock new features in the online world. 

This project allows for the gathering of ever-increasing quantities of images of vegetation, allowing researchers to evaluate their condition and dispersal around the world, while promoting interest and educating the public on biodiversity, nature and plant species. 

The app should promote this endeavour by rewarding the collection on in-game species by creating a library system that stores them, customizable gardens with also unlockable decor, and other types of games and multiplayer interactions. 

In the project we will focus on the creation and fitting of the models on a small sample of relevant species and to create a mock-up of the app and the feature integration in it. 

We determined that the main challenge in our project is the lack of images in currently available databases, as we would need a large quantity for both training and testing our models. We believe that we can collect images from various smaller organizations, whose images can be complemented by photos taken by us.  

Other, problems that we may face include the format of our images, as most will vary in sizes, definition and file type; to combat this we will have to transform most of our images to a predetermined format in the preprocessing stages. 

To evaluate the classification model, we are looking to do calculate the Error matrix and analyse the ROC curve and de AUC over the epochs. We at the moment are unsure what would the best method be to evaluate the segmentation model (maybe using the F1 score, but we will need to analyse it more thoroughly, we are also open to suggestions).