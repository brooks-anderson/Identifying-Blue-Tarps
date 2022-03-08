# Haiti Earthquake Relief Effort: Finding Blue Tarps

### Introduction
This repository represents my final submission for course DS 6030 in the University of Virginia's Master of Science, Data Science.

In the aftermath of the 2010 Haiti earthquake, rescue workers needed a way to find displaced people from aerial photographs. Researchers from Rochester Institute of Technology developed a statiscal model which took pixel RGB values as input and returned probabilites that a given pixel represented a blue tarp, indicating a temporary shelter. The original study can be found here:  
https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.388.2622&rep=rep1&type=pdf

I expand upon this study by comparing eight model types: *k-Nearest Neighbors, Linear Discriminant Analysis, Quadratic Discriminant Analysis, Logistic Regression, Random Forest, Support Vector Machine (polynomial kernel), Support Vector Machine (RBF kernel), Mahalanobis Classifier.* I also develop a framework for visualizing binary classifier decision boundaries in two dimensions.

Random Forest | Support-Vector Machine (Polynomial Kernel)
:------------:|:----------------------------------------:
![image](https://user-images.githubusercontent.com/72112566/157329841-23116f58-f182-4834-a007-97e6c6e13a17.png) | ![image](https://user-images.githubusercontent.com/72112566/157329890-599ec77c-52e3-469b-b8d6-76b24055eeaa.png) 

Additional details, methods, and conclusions can be found in `Finding_Blue_Tarps.pdf`

---
### File Organization
This repository contains three files:
+ `Identifying_Blue_Tarps.Rmd` - Rmarkdown file containing code for preprocessing and model evaluation
+ `Identifying_Blue_Tarps.html` - Rendered Rmarkdown file. Viewable here:  
   https://htmlpreview.github.io/?https://github.com/brooks-anderson/Identifying-Blue-Tarps/blob/main/Identifying_Blue_Tarps.html
+ `Finding_Blue_Tarps.pdf` - PDF presentation of my findings and conclusions

Source data is not provided since I do not have ownership.
