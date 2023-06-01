# README for Natural Scenes Image Dataset

This dataset contains approximately 25,000 images of natural scenes from around the world. The images are of size 150x150 and are distributed across 6 categories: buildings, forest, glacier, mountain, sea, and street. The dataset is divided into train, test, and prediction sets, with approximately 14,000 images in the train set, 3,000 images in the test set, and 7,000 images in the prediction set.

## Data Categories

The dataset contains images from the following categories:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

Each image is labeled with its corresponding category. The label names are mapped to numbers as follows:

- Buildings -> 0
- Forest -> 1
- Glacier -> 2
- Mountain -> 3
- Sea -> 4
- Street -> 5

## File Structure

The dataset is provided in the form of zip files, with separate zip files for the train, test, and prediction sets. Each zip file contains a folder with images in JPEG format. the labels are encoded in the Folders names of the images. Each  belongs to (buildings, forest, glacier, mountain, sea, or street).

```
natural-scenes-image-dataset.zip
│
├── Train
│   ├── Buildings
│   │   ├── buildings_0001.jpg
│   │   ├── buildings_0002.jpg
│   │   ├── ...
│   ├── Forest
│   │   ├── forest_0001.jpg
│   │   ├── forest_0002.jpg
│   │   ├── ...
│   ├── Glacier
│   │   ├── glacier_0001.jpg
│   │   ├── glacier_0002.jpg
│   │   ├── ...
│   ├── Mountain
│   │   ├── mountain_0001.jpg
│   │   ├── mountain_0002.jpg
│   │   ├── ...
│   ├── Sea
│   │   ├── sea_0001.jpg
│   │   ├── sea_0002.jpg
│   │   ├── ...
│   └── Street
│       ├── street_0001.jpg
│       ├── street_0002.jpg
│       ├── ...
├── Test
│   ├── Buildings
│   │   ├── buildings_0001.jpg
│   │   ├── buildings_0002.jpg
│   │   ├── ...
│   ├── Forest
│   │   ├── forest_0001.jpg
│   │   ├── forest_0002.jpg
│   │   ├── ...
│   ├── Glacier
│   │   ├── glacier_0001.jpg
│   │   ├── glacier_0002.jpg
│   │   ├── ...
│   ├── Mountain
│   │   ├── mountain_0001.jpg
│   │   ├── mountain_0002.jpg
│   │   ├── ...
│   ├── Sea
│   │   ├── sea_0001.jpg
│   │   ├── sea_0002.jpg
│   │   ├── ...
│   └── Street
│       ├── street_0001.jpg
│       ├── street_0002.jpg
│       ├── ...
└── Prediction
    ├── prediction_0001.jpg
    ├── prediction_0002.jpg
    ├── ...
```
