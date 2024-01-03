# Plant-Pathology-Disease-Detection
Developed an innovative plant pathology solution using image segmentation, object detection, and ensemble models to accurately identify leaf diseases. Leveraged AI techniques on leaf images, enabling precise disease diagnosis for improved agricultural yield.

Plant Pathology 2021 - FGVC8:

Identify the category of foliar diseases in apple trees
https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8

Description:

Problem Statement:

Apples are one of the most important temperate fruit crops in the world. Foliar (leaf) diseases pose a major threat to the overall productivity and quality of apple orchards. The current process for disease diagnosis in apple orchards is based on manual scouting by humans, which is time-consuming and expensive.

Although computer vision-based models have shown promise for plant disease identification, there are some limitations that need to be addressed. Large variations in visual symptoms of a single disease across different apple cultivars, or new varieties that originated under cultivation, are major challenges for computer vision-based disease identification. These variations arise from differences in natural and image capturing environments, for example, leaf color and leaf morphology, the age of infected tissues, non-uniform image background, and different light illumination during imaging etc.

Plant Pathology 2020-FGVC7 challenge competition had a pilot dataset of 3,651 RGB images of foliar disease of apples. For Plant Pathology 2021-FGVC8, we have significantly increased the number of foliar disease images and added additional disease categories. This year’s dataset contains approximately 23,000 high-quality RGB images of apple foliar diseases, including a large expert-annotated disease dataset. This dataset reflects real field scenarios by representing non-homogeneous backgrounds of leaf images taken at different maturity stages and at different times of day under different focal camera settings.

Specific Objectives:

The main objective of the competition is to develop machine learning-based models to accurately classify a given leaf image from the test dataset to a particular disease category, and to identify an individual disease from multiple disease symptoms on a single leaf image.

Resources:

Details and background information on the dataset and Kaggle competition ‘Plant Pathology 2020 Challenge’ were published as a peer-reviewed research article. If you use the dataset for your project, please cite the following

Thapa, Ranjita; Zhang, Kai; Snavely, Noah; Belongie, Serge; Khan, Awais. The Plant Pathology Challenge 2020 data set to classify foliar disease of apples. Applications in Plant Sciences, 8 (9), 2020.

CVPR 2021:

This competition is part of the Fine-Grained Visual Categorization FGVC8 workshop at the Computer Vision and Pattern Recognition Conference CVPR 2021. A panel will review the top submissions for the competition based on the description of the methods provided. From this, a subset may be invited to present their results at the workshop. Attending the workshop is not required to participate in the competition, however only teams that are attending the workshop will be considered to present their work.

Citation:

Thapa, Ranjita; Zhang, Kai; Snavely, Noah; Belongie, Serge; Khan, Awais. (2021). Plant Pathology 2021 - FGVC8 . Kaggle. https://kaggle.com/competitions/plant-pathology-2021-fgvc8

Dataset Description:

Can you help detect farmers detect apple diseases? This competition builds on last year's by challenging you to handle additional diseases and to provide more detailed information about leaves that have multiple infections.

Files:

train.csv - the training set metadata.

image - the image ID.

labels - the target classes, a space delimited list of all diseases found in the image. Unhealthy leaves with too many diseases to classify visually will have the complex class, and may also have a subset of the diseases identified.

sample_submission.csv - A sample submission file in the correct format.

train_images - The training set images.

test_images - The test set images. This competition has a hidden test set: only three images are provided here as samples while the remaining 5,000 images will be available to your notebook once it is submitted.
