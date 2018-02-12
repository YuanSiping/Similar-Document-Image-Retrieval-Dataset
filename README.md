# Similar-Document-Image-Retrieval-Dataset
The benchmark collection named Similar-Document-Image-Retrieval-Dataset(SDIRD) is provided for a task, which is finding out the similar document images for a query document image. The structure of SDIRD is as follows:
```
├── database
├── databaseClassified
├── queryset
├── trainingset
└── database-subject
```
######database
This is the document image database with 10240 document images.
######databaseClassified
This directory collects the images of above database according to corresponding original source(148 papers).
######queryset
This is the query image dataset with 1000 images totally.
######trainingset
This is the target dataset to fine-tune pre-trained CNN models, which including training set and validation set
######database-subject
