# Prepare Datasets

We provide instructions for accessing the datasets.

## Dataset Overview

The training dataset consists of two classes [Fsqurriel, mouse] 

The validation dataset consists of one class [chipmunk]

The images of [Fsqurriel, mouse] classes are split into 80% training and 20% validation.

The images of the [chipmunk] class are set as validation data which means the model does not see them during training

The dataset is in COCO format and it is organized as follows:

```
coco/
  annotations/
    instances_train2017_base.json          # training dataset
    instances_val2017_basetarget.json      # validation dataset
  train2017/
    images for the training dataset
  val2017/
    images for validation dataset
```
## How TO Use The Dataset

in the training script, pass the path to the dataset as 
```
--coco_path /mnt/ceph/alha0230/Rodent/coco

```



