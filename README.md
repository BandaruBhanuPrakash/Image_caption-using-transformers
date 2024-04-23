MSCOCO is the Dataset used for this project.
As the Dataset size is large, it can't upload in to the Google drive so we are using the Zip files to get the dataset(From coco official website)

**Zip file links:**
!wget http://images.cocodataset.org/zips/train2017.zip -O coco_train2017.zip ----- For training Dataset
!wget http://images.cocodataset.org/zips/val2017.zip -O coco_val2017.zip --------- For validation Dataset
!wget http://images.cocodataset.org/annotations/annotations_trainval2017.zip -O coco_ann2017.zip  ---  For annotations 

This project is done by using transformers(InceptionV3 + Imagenet).
The results are accurate for the dataset images and getting less accuracy for the other images apart from the dataset.

**OUTPUT for dataset images**
![image](https://github.com/BandaruBhanuPrakash/Image_caption-using-transformers/assets/123976110/b7e6a0e7-bd02-48f8-85bd-43136181b126)
