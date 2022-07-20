# Melanoma detection assignment

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
- First model wasn't performing good as it suffered from overfitting.
- To overcome overfititng, we added dropout layers and earlystopping. This helped us to fix the overfitting but reduced the overall performance of the model.
- Batch Normalization and Augumentation helped in fixing class imbalancing problem although the val score came out to be unstable.

## Technologies Used
- pandas 1.3.4
- matplotlib 3.4.3
- seaborn 0.11.2
- tensorflow 2.9.1
