# Eyeconic_Coders_MINeD2025
# Malware Detection Using Machine Learning

## Team: EYECONIC CODERS

## Introduction
This project was developed as part of the **Mined Hackathon 2025 at Nirma University**. The objective was to design and implement a **machine learning model** to classify malware into different categories based on given dataset features. Our model enhances cybersecurity by improving malware detection accuracy and efficiency.

## Objective
The goal of this project is to:
- Build a **machine learning model** that classifies malware samples into predefined categories.
- Utilize **feature engineering techniques** to optimize performance.
- Improve generalization to detect **new malware variants** effectively.

## Dataset
The dataset contains three types of features:
1. **Portable Executable (PE) Headers**: Includes 52 PE header fields and 9 field values of 10 PE sections.
2. **DLL Imports**: Contains the DLLs used by different malware families (629 types).
3. **API Function Calls**: Lists 21,918 API functions used by each executable.

The dataset was preprocessed to remove inconsistencies and irrelevant data, ensuring a robust training process.

## Model Architecture and Approach
We used a combination of **Random Forest Classifier** and **Dask** to improve performance:

- **Feature Engineering with Dask**: Enabled parallel computing for handling large datasets efficiently.
- **Random Forest Classification**: Helped in avoiding overfitting and provided robust classification.
- **Ensemble Learning**: Used multiple decision trees to improve accuracy and generalization.

## Preprocessing & Feature Engineering Techniques
To ensure high model accuracy and efficiency, we performed the following:
- **Data Cleaning & Normalization**: Removed inconsistencies and scaled data for better performance.
- **Feature Engineering with Dask**: Used Dask's parallel processing capabilities to efficiently handle large-scale feature extraction and transformation.
- **Handling High-Dimensional Data**: Random Forest efficiently handled high-dimensional inputs.
- **Data Splitting**: The dataset was divided into **training** and **testing** sets to ensure reliable evaluation.

## Challenges Faced & Solutions
### 1. High Computational Cost
- **Issue**: Random Forest requires high computational resources due to multiple decision trees.
- **Solution**: We optimized the number of trees and used Dask for efficient parallel processing.

### 2. Training on Large Datasets
- **Issue**: Training on high-dimensional data was slow and resource-intensive.
- **Solution**: Dask enabled scalable computations, significantly improving training times.

### 3. Generalization to New Malware Variants
- **Issue**: The model struggled to detect unseen malware samples.
- **Solution**: Future improvements will include **adaptive learning** to dynamically update the model as new threats emerge.

## Deliverables
- **Machine Learning Model** for malware classification.
- **Preprocessing & Feature Engineering Scripts**.
- **Report detailing Model Architecture, Challenges, and Findings**.
- **Presentation on the approach and results**.
- **Test dataset predictions and trained model file**.

## Future Enhancements
- Implement **Deep Learning** techniques for better feature extraction.
- Utilize **Adaptive Learning** for real-time malware detection.
- Explore **Federated Learning** to improve security while training the model.

## Contributors
- **Shomya Soneji**
- **Priyanshi Jhala**
- **Reyan Shah**
- **Misty Thummar**

## Acknowledgment
This project was part of the **Mined Hackathon 2025** at **Nirma University**, supported by **Crest Data Systems**.

## License
This project is licensed under the **MIT License**. Feel free to contribute and improve the model!
