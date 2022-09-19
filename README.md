

Bone marrow cytology is required to make a hematological diagnosis, influencing critical clinical decision points in hematology. However, bone marrow cytology is tedious, limited to experienced reference centers and associated with high inter-observer variability. This may lead to a delayed or incorrect diagnosis, leaving an unmet need for innovative supporting technologies. We have developed the first ever end-to-end deep learningbased technology for automated bone marrow cytology. Starting with a bone marrow aspirate digital whole slide image, our technology rapidly and automatically detects suitable regions for cytology, and subsequently identifies and classifies all bone marrow cells in each region. This collective cytomorphological information is captured in a novel representation called Histogram of Cell Types (HCT) quantifying bone marrow cell class probability distribution and acting as a cytological “patient fingerprint”. The approach achieves high accuracy in region detection (0.97 accuracy and 0.99 ROC AUC), and cell detection and cell classification (0.75 mAP, 0.78 F1-score, Log-average miss rate of 0.31). HCT has potential to revolutionize hematopathology diagnostic workflows, leading to more cost-effective, accurate diagnosis and opening the door to precision medicine.

Link to the paper: https://www.nature.com/articles/s43856-022-00107-6

Link to the full implementation and network weights: https://kimialab.uwaterloo.ca/kimia/index.php/roi-detection-and-cell-detection-and-classification-in-bone-marrow-cytology/


#### \- End-to-end AI architecture for bone marrow aspirate cytology:

![image](https://user-images.githubusercontent.com/36484259/191070810-e357ccd2-b80b-4392-b083-13b2b5fc88c6.png)

\- Applying the region of interest (ROI) detection model:

![image](https://user-images.githubusercontent.com/36484259/191071324-ccb438a1-f212-4f47-841c-15745c5b4b7f.png)

\- Applying the YOLO model to localize objects in selected region of interest (ROI) tiles:

![image](https://user-images.githubusercontent.com/36484259/191071382-e71b5483-b37c-4c6e-a9b3-ca8f0d3f9f80.png)

\- Generating the Histogram of Cell Types (HCT) and converged Integrated Histogram of Cell Types:

![image](https://user-images.githubusercontent.com/36484259/191071496-e8354b27-6967-4fc5-b80d-e5a73666917d.png)
