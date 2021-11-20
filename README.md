# Better segmentation images for opencv seamless cloning

### Copy the code from [here](https://github.com/Dav00Arm/Segmentation_masks/blob/main/Seamless_Clone.ipynb), run it, and call <data_creation> function with required arguments. 

While creating new image data with [Seamless Clone using Opencv](https://learnopencv.com/seamless-cloning-using-opencv-python-cpp/) there might be cases that you dont get clean output images.

### For example 

##### Source image,mask and backgorund
![src](https://github.com/Dav00Arm/Segmentation_masks/blob/main/images/image.png)
![mask](https://github.com/Dav00Arm/Segmentation_masks/blob/main/images/mask_clone.jpg)
![background](https://github.com/Dav00Arm/Segmentation_masks/blob/main/images/background.png)

#### regular seamless clone                                   
It performes terrible on very small masks 
![regular_clone](https://github.com/Dav00Arm/Segmentation_masks/blob/main/images/normal_clone.jpg)

#### Clone using <data_creation>
But this function helps to get perfectly created new image 
![better_clone](https://github.com/Dav00Arm/Segmentation_masks/blob/main/images/better_clone.jpg)
