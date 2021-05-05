# <a name="top">cNN Image Classification</a>

This project used Python and TensorFlow to explore convolutional neural nets.A Powerpoint was used as an endpoint presentation, in which I discuss how I explored the data, built a series of models, and analyze the results. The purpose was more to gain a better understanding of the leavers used to control models in TF, and the best model recorded achieved an accuracy of %84. A number of prediction samples are looked at, and the errors discussed.  
______________________________________________

## Links
- [Intel Image Dataset](https://www.kaggle.com/puneet6060/intel-image-classification)
Kaggle project hosting the dataset
- [cNN Presentation](https://docs.google.com/presentation/d/15pTsUTayuuk3Yjr66WRyAtrebqUAKJjbbTBJont3CSU/edit?usp=sharing)
A google docs hosting my original presentation


## Data

The [Intel Image Dataset](https://www.kaggle.com/puneet6060/intel-image-classification) consists labeled photos of scenery. 

![Example](images/building-examp.png)
- 'buildings' -> 0 
- 'forest' -> 1,
- 'glacier' -> 2,
- 'mountain' -> 3,
- 'sea' -> 4,
- 'street' -> 5 

The data was originally provided by Intel for data science competitions, and was found on open Kaggle project. The categories are relatively evenly distributed, and the set includes training, testing, and unlabeled images. Samples were resized and normalized before training. 

- 14,034 Training Image
- 3000 Testing Images
- 7000 Non-labeled Images
![Testing Pie](images/testing-cats.png)
![Training pie](images/training_cats.png)




