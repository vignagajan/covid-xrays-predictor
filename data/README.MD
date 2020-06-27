# Compile COVID x-rays image dataset

Image dataset created for predicting a person has affected by coronavirus or not by using his x-ray images. For this purpose, we used two public datasets.

1. [Kaggle Pneumonia Chest Xrays dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

![alt text](https://i.imgur.com/jZqpV51.png)

**Illustrative Examples of Chest X-Rays in Patients with Pneumonia.**

> The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs.

>


2. [COVID Chest Xrays Dataset Repo](https://github.com/ieee8023/covid-chestxray-dataset)

**Data collected on behalf of the research paper.**

>COVID-19 Image Data Collection: Prospective Predictions Are the Future, arXiv:2006.11988, 2020
Joseph Paul Cohen and Paul Morrison and Lan Dao and Karsten Roth and Tim Q Duong and Marzyeh Ghassemi
<https://github.com/ieee8023/covid-chestxray-dataset>
>

***

## Preparation

1. In the Kaggle dataset, Normal and Pneumonia images were split into the train, validation, and test sets. They have been extracted and combined.

2. COVID chest x-rays images were extracted from the COVID dataset.

3. Images dataset is created by combining all Normal, Pneumonia, and COVID x-rays in an equal amount (So far COVID x-rays are small in amount compared to Normal and Pneumonia images)

**As the COVID original updated with time, final dataset created with the filename of creation date.** 

## Next Steps

Create a predictor to identify whether the patient is affected by either Pneumonia or COVID or Normal, with the help of deep learning. 

## Contributing

All the codes (*ipython notebooks*) on the collection and compilation of the images are also uploaded in this repo.

Please open an issue first to discuss or share your suggestions on my work!



## License
[MIT](https://choosealicense.com/licenses/mit/)
