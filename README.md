# Food-Image-Classification-with-small-sample-learning
using small sample food images to train classification model

please download the food images from: https://cbc-developer-res-intl.obs.myhwclouds.com/competition/aifood_en.zip

There are 2 types training dataset: one contains 75 categories food with 100-1000 per category and one contains 25 categories 
with 5 per category.

The "small_images" is enhanced dataset using "small_image_enhancement.ipynb".

"transfer_learning.ipynb" use Inception_V3 pre-trained model to extract features of 25-category
food images, and build top classifer model to classify 25 categories food images.




