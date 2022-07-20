# melanoma-detection_assignment

### Problem Statetment
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



### Steps
- Import library
- Read Data
- Data understanding
- Dataset Creation
- Dataset visualisation
- Model Building & training 
- Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
- Model Building & training on the augmented data 
- Class distribution
- Handling class imbalances
- Model Building & training on the rectified class imbalance data
- Conclusion

## Conclusions
- Initial model didnt perform well because it suffers from overfitting.
- To reduce overfititng we added dropout layers and earlystopping , which helped fix overfitting but it reduced the overall performance of the model.
- We tried Batch Normalization and Augumentation which helped in fixing class imbalancing problem but val score seems to be unstable.

## Technologies Used
- pandas 1.3.5
- matplotlib 3.5.2
- seaborn 0.11.2
- tensorflow 2.9.1
