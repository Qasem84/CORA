# Prepare Datasets

We provide instruction for preparing datasets.

## Overview

The dataset is in COCO format. It has 3 classes [ chipmunk, mouse, Fsqurriel]

The training data includes 80% of [ mouse, Fsqurriel] classes images.

The validation data includes 20% of [mouse, Fsqurriel] classes and all chipmunk images.


## Dataset structure

```
coco/
  annotations/
    instances_train2017_base.json  # for training data
    instances_val2017_basetarget   # for validation data
 train2017/
    images for training data
 val2017/
    images for validation data
    
```

## Dataset path

in the training script use: 

'''
--coco_path /mnt/ceph/alha0230/Rodent/coco


