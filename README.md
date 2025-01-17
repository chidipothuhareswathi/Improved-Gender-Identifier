About the dataset: The IMDB dataset contains 460,723 facial images (with gender and age labels) of film stars, predominantly Hollywood actors and actresses, and the Wikipedia dataset includes 62,328 of celebrities from various fields, such as sports, politics, social events, and the film industry. These datasets can be accessed from https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/.


The IMDB and WiKi datasets provides metadata such as a face score, a second face score, age, and gender labels on each image. Images with only one frontal face have high face scores, while those with more than one face or profile faces have low scores. The second face scores indicate how clearly a second face is shown in the image. We further selected the facial images with a single face, which is mostly frontal. To achieve it, we chose images with a face score equal to or above 4.5 in the IMDB dataset and equal to or above 5 in the Wikipedia dataset, where the second face score indicated no other face. Finally, the IMDB and Wikipedia datasets contain 33,147 and 3,209 facial images respectively. In GESIS dataset contains 3,323 images (with gender) of various people from the world. 

Then, the original color facial images were converted into 100-by-100 gray-scale images. We created the csv files provided from these datasets that we used. The first column is the index column, the second is the gender, the third is the age for IMDB and WiKi, and the remaining 10,000 correspond to the pixels of the gray-scale image. 

Here, Female = 0
and   Male   = 1
