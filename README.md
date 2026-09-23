# Rose-Leaf-Disease-Detection

Detecting rose leaf diseases (Black Spot, Downy Mildew) from leaf images using transfer learning

## Dataset

[FlowerNet](https://data.mendeley.com/datasets/7z67nyc57w/2) — 917 images across 3 classes (Fresh Leaf, Black Spot, Downy Mildew), photographed at the Village of Roses (Golap Gram), Birulia, Dhaka, Bangladesh.

## Approach

- Augmented each class up to 4x the size of the largest class
- Resized every image to 224x224x3
- Split the dataset 70/15/15 into train/val/test
- To evaluate the performance used ResNet50 and VGG16 

## Result

| Model    | Accuracy | Training Time |
|----------|----------|----------------|
| ResNet50 | 89.69%   | 452.65s        |
| VGG16    | 90.53%   | 526.55s        |


## Citation

> Rajbongshi, Aditya; Sazzad, Sadia; Shakil, Rashiduzzaman; Akter, Bonna; Kaiser, M Shamim (2022), "FlowerNet: An extensive rose leaves dataset for disease recognition applying machine learning and deep learning models", Mendeley Data, V2, doi: 10.17632/7z67nyc57w.2

