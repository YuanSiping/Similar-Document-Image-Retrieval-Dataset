# Similar-Document-Image-Retrieval-Dataset
The benchmark collection named Similar-Document-Image-Retrieval-Dataset(SDIRD) is provided for a task, which is finding out the similar document images for a query document image. The structure of SDIRD is as follows:
```
├── database
├── databaseClassified
├── queryset
├── trainingset
└── database-subject
```
###### database
This is the document image database with 10240 document images.
###### databaseClassified
This directory collects the images of above database according to corresponding original source(148 papers).
###### queryset
This is the query image dataset with 1000 images totally.
###### trainingset
This is the target dataset to fine-tune pre-trained CNN models, which including training set with 1000 document images and validation set with 200 images, and the label or category information.
###### database-subject
This is the information of document image database about the category id, category label,  the number of images from corresponding paper and title.
###### performance
Methods|Top-1(%)|Top-3(%)|Top-5(%)|Top-10(%)
------------- | -------------| -------------| -------------| -------------
GoogLeNet | 8.3 | 13.8 | 17.3 | 21.6
ResNet-152 | 17.2 | 24.7 | 28.6 | 35.2
AlexNet | 32.6 | 45.0 | 51.6 | 59.6
Fine-tuned-AlexNet | 37.5 | 54.1 | 60.9 | 69.8
VGGNet-D | 22.8 | 34.0 | 39.3 | 46.9
Fine-tuned-VGGNet-D | 37.2 | 56.2 | 64.6 | 76.5
VGGNet-E | 24.1 | 37.5 | 44.1 | 53.2
Fine-tuned-VGGNet-E | 46.8 | 68.9 | 79.3 | 90.0
Ours| 54.1| 82.9| 97.3| 100.0
Ours| 58.8| 86.4| 94.5| 98.9
