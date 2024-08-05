# ABSTRACT
The Philippines grapples with a critical waste management challenge, largely driven by its "sachet economy." This economic model relies heavily on single-use plastic packaging, leading to an alarming accumulation of non-biodegradable waste. Overflowing landfills and inadequate waste segregation further exacerbate the problem. While manual sorting in Materials Recovery Facilities (MRFs) remains common, scalability is a major hurdle. Automating MRFs presents an opportunity to leverage object detection models. This study aimed to develop a YOLO-v8 based model using publicly available image datasets. However, initial performance on a Philippine waste test set yielded a disappointing mean Average Precision (mAP@50) of 23%. Analysis revealed significant data discrepancy between training and test data, and to address this, we implemented web scraping to augment the training data with Philippine-specific waste images. This data augmentation strategy significantly improved model performance, achieving a mAP@50 of 71% on the test set.

# METHODOLOGY
![image](https://github.com/user-attachments/assets/cf2723d1-40c0-461d-ae6f-33aa67349da9)



