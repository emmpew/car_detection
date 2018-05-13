# Car Detection

The goal and challenge in computer vision is basically to detect and find objects in images. The problem is that one class such as cars can have different shapes, sizes, color, angles, complex backgrounds and an issue with scaling. The project aims to detect cars from all these different scenarios given a single image or frame of a video. The project covers the following:

- Performed feature extraction using Histogram of Oriented Gradients
- Used the classifier LinearSVC for training and testing 
- Implemented a sliding window to create bounding boxes if object is detected
- Applied a heatmap to cluster bounding boxes and reject outliers
- Tested the classifier on a static video shot with an iPhone
- Improved detection by using data augmentation

The data was collected from [GTI website](https://www.gti.ssr.upm.es/data/Vehicle_database.html). The database comprises 3425 images of vehicle rears taken from different points of view, and 3900 images extracted from road sequences not containing vehicles.

