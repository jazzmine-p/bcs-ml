# Breast Cancer Detection
This project aims to predict whether an individual has breast cancer and determine which cytological attributes are significant in identifying benign and malignant tumors.

The markdown can be viewed on [RPubs](https://rpubs.com/jazzmine/breast-cancer-ml)

## Problem Identification
Breast cancer is the second most common and also the second leading cause of cancer deaths in women in the United States. According to the American Cancer Society, on average every 1 in 8 women in the United States would develop breast cancer in her lifetime and 2.6% would die from breast cancer. One of the warning symptoms of breast cancer is the development of a tumor in the breast. A tumor, however, could be either benign or malignant.

## Objective
This project aims to predict whether an individual has breast cancer and determine which cytological attributes are significant in identifying benign and malignant tumors. To achieve this, I performed four different classification models in machine learning, namely Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting Machine, on a dataset obtained from the UCI Machine Learning Repository. This dataset was created by Dr. William H. Wolberg from the University of Wisconsin, who took a digital scan of the fine-needle aspirates from patients with solid breast masses. Then, he used a graphical computer program called Xcyt to calculate ten cytological characteristics present in each digitized image. These features are as follows:

| #  | Attribute                     | Domain   |
|----|-------------------------------|----------|
| 1  | Sample Code Number            | ID number|
| 2  | Clump Thickness               | 1 - 10   |
| 3  | Uniformity of Cell Size       | 1 - 10   |
| 4  | Uniformity of Cell Shape      | 1 - 10   |
| 5  | Marginal Adhesion             | 1 - 10   |
| 6  | Single Epithelial Cell Size   | 1 - 10   |
| 7  | Bare Nuclei                   | 1 - 10   |
| 8  | Bland Chromatin               | 1 - 10   |
| 9  | Normal Nucleoli               | 1 - 10   |
| 10 | Mitoses                       | 1 - 10   |

## Approach
- EDA
- Data Processing and Feature Engineering
- Models Building and Fine Tuning (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting Machine)
- Models Evaluation and Selection
  
## Conclusion
In this project, I created four classification machine learning models that can predict if a person has breast cancer based on digitized image readings of patients’ fine-needle aspirates. The best performing model, the gradient boosting, correctly classifies patients with and without breast cancer 95.3% of the times. Its AUC of 99.1% indicates a great ability to distinguish between a benign lump and a malignant tumor. The final model also has a lift metric of 2.2, meaning that it’s more than twice as good as randomly guessing. 
The top cytological characteristics in identifying breast cancer are the uniformity of cell size, the uniformity of cell shape, the uniformity of nucleus texture, and the thickness of the clump.
