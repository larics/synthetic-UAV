
![eagle_005](https://user-images.githubusercontent.com/26712043/133765314-4409dde7-f5ae-44b3-b69a-548bf368f553.png)

A synthetic dataset for object detection of UAVs
----

This repository contains a synthetic datasets accompanying the paper **Sim2Air - Synthetic aerial dataset for UAV monitoring** by Antonella Barisic, Frano Petric and Stjepan Bogdan.

In this paper, we propose to use a texture-invariant representation of objects for aerial object detection. Our approach improves the generalisation and robustness of the object detector. A dataset is created with randomly assigned atypical textures and sufficient diversity and photorealism in all other components such as shape, pose, lighting, scale, background, etc. The results also show improved accuracy in case of distant objects and difficult lighting conditions.

All datasets from the paper are available for [download](https://ferhr-my.sharepoint.com/:f:/g/personal/abarisic1_fer_hr/Er3AKC69wNVOoXVv3_rP6ikBpLyYKOwLr8_9zXZVF2dVeQ?e=lfm0vT&download=1). If you use these datasets for your research, please cite:
```
@unpublished{sim2air,
author = {Antonella Barisic and Frano Petric and Stjepan Bogdan},
title = {Sim2Air - Synthetic aerial dataset for UAV monitoring},
note = {Manuscript submitted for publication},
year = {2021}
}
```

## Datasets

| Name | Description |
| ------ | ----------- |
| **S**ynthetic **E**agle **B**aseline (**SEB**)|The SEB dataset is a synthetic dataset with a single UAV model, the custom aerial platform Eagle. Since this dataset serves as the basis for proving our hypothesis, it was created with only one texture, identical to the texture of real-life Eagle. SEB consists of 32 000 images of size 604 x 604 with annotations in YOLO format. |
| **S**ynthetic **E**agle with **T**extures (**SET**)| The SET dataset is the main star :star: of our work. It is a synthetic dataset of a single model, the custom aerial platform Eagle, with randomly selected atypical textures. The mixture of 32 different textures is applied during the procedural generation of the dataset. SET also consists of 32 000 images of size 604 x 604 with annotations in YOLO format. |
| **S**ynthetic **UAV**s with **T**extures (**S-UAV-T**)| The S-UAV-T dataset is similar to SET but with many more models of UAVs. The data was created with 10 different multicopter models, 32 atypical textures, and with a variety of poses, backgrounds, viewpoints, etc. S-UAV-T consists of 52 500 images of size 604 x 604 with annotations in YOLO format. |

If you want to test your detection results against real data, check out our **UAV-Eagle dataset** at [larics/UAV-Eagle](https://github.com/larics/UAV-Eagle).


## Contact

For more information, please contact [Antonella Barisic](mailto:antonella.barisic@fer.hr).

