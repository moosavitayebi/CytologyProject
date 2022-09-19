

Bone marrow cytology is required to make a hematological diagnosis, influencing critical clinical decision points in hematology. However, bone marrow cytology is tedious, limited to experienced reference centers and associated with high inter-observer variability. This may lead to a delayed or incorrect diagnosis, leaving an unmet need for innovative supporting technologies. We have developed the first ever end-to-end deep learningbased technology for automated bone marrow cytology. Starting with a bone marrow aspirate digital whole slide image, our technology rapidly and automatically detects suitable regions for cytology, and subsequently identifies and classifies all bone marrow cells in each region. This collective cytomorphological information is captured in a novel representation called Histogram of Cell Types (HCT) quantifying bone marrow cell class probability distribution and acting as a cytological “patient fingerprint”. The approach achieves high accuracy in region detection (0.97 accuracy and 0.99 ROC AUC), and cell detection and cell classification (0.75 mAP, 0.78 F1-score, Log-average miss rate of 0.31). HCT has potential to revolutionize hematopathology diagnostic workflows, leading to more cost-effective, accurate diagnosis and opening the door to precision medicine.

Link to the paper: https://www.nature.com/articles/s43856-022-00107-6

Link to the full implementation and network weights: https://kimialab.uwaterloo.ca/kimia/index.php/roi-detection-and-cell-detection-and-classification-in-bone-marrow-cytology/


![image](https://user-images.githubusercontent.com/36484259/191070505-282c9b0a-43b7-4b65-ab69-794a1eb74d4e.png)
![image](https://user-images.githubusercontent.com/36484259/191070553-b6247ae8-3136-4aa8-90ae-528ade9c1c7d.png)
