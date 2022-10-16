# Detect the road by using matlab


The goal of the project is to detect boundaries of roads and fields. This project aims to identify the different line features in images that delineate fields such as roads, canals, or trails. The fact that the roads are not necessarily consistent in size, color, and shape makes this somewhat challenging. The techniques used in this project could potentially be used by a navigation software developer or a space-based photography company to draw the road from the ground truth images, or to identify the boundary of the road for future autonomous cars. (Howe, J., Casterline , M., & Brown, A. ,2022)


![alt text](https://github.com/bring-nirachornkul/Road-Detection/blob/master/Expected%20photo.png?raw=true)


## Member of this project

1. Phongsiri Nirachornkul  : Coder, Presentation builder
2. John Lage               : Coder, documentation
3. Ibrahim Alkuwaifi       : Documentation


# Progress

We found a lot of TN (True Negative), the missing line ,and FP (False Positive), aka. unnecessary lines during evaluation. The only thing we need here is True positive, the line that matched on road.

![alt text](https://github.com/bring-nirachornkul/Road-Detection/blob/master/Compare%20and%20contrast.png?raw=true)

Our plan to obtain the ground-truth image (expected outcome) is to find the middle zone between overfitting and underfitting the line mark in hough transformation. We will compare ground-truth image (expected outcome) with the result from the generated image via hough transformation by MAP (mean average precision). 
