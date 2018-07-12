# Identify the animal 

Model to Identify the animal present in the image.

- The training dataset has 13000 image
- The test dataset has 6000 images

**There are 30 different animal species in the dataset :**

antelope, bat, beaver, bobcat, buffalo, chihuahua, chimpanzee, collie, dalmatian, german shepherd, grizzly bear, hippopotamus, horse, killer whale, mole, moose, mouse, otter, ox, persian cat, raccoon, rat, rhinoceros, seal, siamese cat, spider monkey, squirrel, walrus, weasel, wolf

**I have used the following models with Pre-trained weights on ImageNet**

- ResNet50
- InceptionResNetV2

## Results on different models:

| Model | Epochs | Training | Validation | Test |
| ----- | ------ | -------- | ---------- | ---- |
| ResNet50 | 10 | 92.80 | 93.20 | 87.24 |
| ResNet50 | 20 | 97.35 | 92.89 | 85.3 |
| InceptionResNetV2 | 5 | 92.13 | 95.08 | 92.92 |
| InceptionResNetV2 | 10 | 95.97 | 95.47 | 93.37 |
