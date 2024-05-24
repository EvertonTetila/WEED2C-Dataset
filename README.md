# WEED2C-Dataset

Soybean weed image dataset.

![fig2](https://github.com/EvertonTetila/WEED2C-Dataset/assets/37840161/6fd83779-5cd5-4cf7-842a-4a03c2234975)

# Image acquisition

We used the UAV at an altitude of 10 meters from the plantation to create a reference collection of weeds in soybean. The UAV is a multirotor Phantom 4 Advanced model equipped with a 20MP Sony camera. During the 2020/21 harvest, three agricultural areas were flown over and 1,140 images were collected during the phenological stages V3, V4, and V5, considered of high occurrence of weeds in soybean fields. The crop images were collected on different days, locations, and weather conditions, which provide unwanted variations in lighting, phenological stages, blurring (drag), and complex crop backgrounds.

The agricultural areas are located in the municipalities of Caarapó-MS and Dourados-MS, Brazil. JPG images were collected by the UAV using a resolution of 5472x3648 pixels and 80% frontal and side overlap. To exclude information redundancy from the overlapping area, we cropped the orthomosaic images using a 1920x1080 pixels resolution. Out of the total images, we observed the presence of weeds in 763 images that we are using in our dataset.

With the support of a field expert Agronomist, each dataset image was annotated in Labellmg https://github.com/tzutalin/labelImg, thus building a reference collection for the training and testing dataset of the system called WEED2C-Dataset.

# Acknowledgements

This dataset was created by the authors and should be cited as follows:
