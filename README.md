# parkinsonism-gait-analysis
Graduation project on Parkinsonian Gait Severity in Older Adults with Dementia using Natural Gait Video Analysis
# Parkinsonian Gait Severity Analysis in Older Adults with Dementia

## Summary

This project focuses on analyzing Parkinsonian gait severity in older adults with dementia using natural gait video analysis. The research aims to develop a machine learning-based approach to assess gait patterns and their correlation with Parkinson's disease symptoms in the target population. By leveraging vision-based systems and advanced machine learning algorithms, this study provides a non-invasive and efficient method for clinical assessment and monitoring of gait abnormalities.

## Publication Achievement

We are proud to announce that our research paper, titled "Parkinsonian Gait Severity in Older Adults with Dementia Using Natural Gait Video Analysis," has been published by IEEE. This publication is a significant milestone and a testament to the hard work and dedication of our team.

![IEEE](https://github.com/eissa2002/parkinsonism-gait-analysis/assets/96894512/96dd4759-5ca4-44d0-810d-e81f50b27f64)

<img src="https://github.com/eissa2002/parkinsonism-gait-analysis/assets/96894512/96dd4759-5ca4-44d0-810d-e81f50b27f64" alt="Flowchart" width="800">


## Conference Award

Our project won 2nd place at the International Scientific Student Conference of the Faculty of Nursing, held at Misr University for Science and Technology from April 20 to 24, 2024. This recognition highlights the impact and relevance of our research in the field of healthcare and artificial intelligence.

## Project Process

### 1. Data Collection

We systematically amassed video recordings of fourteen elderly individuals in a meticulously controlled environment, emphasizing the capture of authentic and unaltered gait patterns. Employing high-resolution cameras with the capability of capturing elevated frame rates was imperative to preserve the precision of motion capture, effectively addressing the challenge of faithfully recording the nuanced gait dynamics exhibited by elderly individuals.

### 2. Feature Extraction using MediaPipe

The initial step involved extracting pose estimation data at a temporal resolution of one second per frame. This fine-grained approach ensured a nuanced representation of dynamic gait patterns. Leveraging MediaPipe, we meticulously extracted pivotal gait features from the video footage. The sophisticated pose estimation model within MediaPipe provided exact coordinates of body joints.

### 3. Labeling the Features

The features extracted via MediaPipe underwent a dual labeling process facilitated by expert analysis and K-Means clustering. This dual approach categorically assigned features into distinct gait patterns, combining expert insight with algorithmic clustering to ensure a nuanced understanding of gait patterns.

### 4. Feature Selection

In this critical phase, advanced feature selection techniques were meticulously applied to refine the dataset for subsequent model development. The objective was to identify and retain the most discriminative features crucial for comprehensive gait analysis. The extracted data underwent classification based on the Unified Parkinson's Disease Rating Scale (UPDRS), categorizing individuals into three distinct disease levels (0, 1, 2).

### 5. Clustering

Utilizing clustering techniques, we visualized distinct clusters within the dataset. This step provided a comprehensive view of the inherent patterns and relationships within the data, especially highlighting the cluster associated with different disease severity levels.

### 6. Standard Deviation Analysis

Following the identification of the disease severity cluster with the highest standard deviation, we strategically replaced the assigned level for individuals within that cluster. This adjustment enhanced the precision of our subsequent model development, ensuring that the dataset accurately reflected the variability in disease severity.

### 7. Model Development

With the refined dataset, we proceeded to develop and assess the performance of five machine learning models: K-Nearest Neighbors (KNN), Random Forest, Extra Trees, Logistic Regression, and XGBoost. Each model's performance was evaluated using metrics such as accuracy, recall, F1 score, and precision.

### 8. Model Evaluation

Each model's performance was evaluated using metrics such as accuracy, recall, F1 score, and precision, providing a comprehensive assessment of their classification capabilities and predictive accuracy. The evaluation highlighted significant differences in model performances, with KNN, Random Forest, and Extra Trees showing strong results, whereas Logistic Regression lagged, reflecting the complexity and challenges inherent in the dataset. XGBoost's performance indicates its robustness and adaptability in dealing with structured data.

### 9. Model Refinement and Deployment

The best-performing model underwent further refinement and was prepared for deployment. This step ensures that the model is optimized for real-world application, providing a reliable tool for clinical assessment and monitoring of gait abnormalities.

## Flowchart

![Flowchart](https://github.com/eissa2002/parkinsonism-gait-analysis/assets/96894512/94006082-6796-4a03-b838-2ce3f9a554b1)

## Authors

- Eissa Islam
- Mariam Medhat
- Mohamed Ali
- Farah Waleed
- Ahmed Fathy

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
