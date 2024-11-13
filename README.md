📱 Human Activity Recognition through Multivariate Analysis

This project aims to recognize human activities using smartphone sensor data and multivariate analysis techniques. By applying dimensionality reduction and clustering, this project provides a comprehensive approach to classify activities like standing, walking, and more based on sensor readings.

📊 Project Overview

The project workflow includes:
	1.	Data Collection and Preprocessing: The dataset contains 561 columns of smartphone sensor readings corresponding to various activities performed by participants.
	2.	Dimensionality Reduction (PCA): To handle the high dimensionality, Principal Component Analysis (PCA) was used, reducing the 561 columns to a smaller number of principal components, capturing the essential variance.
	3.	Clustering Analysis:
	•	K-means Clustering: Groups data based on similarity in the principal component space.
	•	Hierarchical Clustering: Using single, complete, and Ward linkage methods to explore hierarchical relationships between activities.
	4.	Visualization: Scatter plots and dendrograms help visualize the clustering results and the principal components’ variance.
	5.	Evaluation: Cluster quality and PCA performance are evaluated based on explained variance and interpretability of clusters.

📂 Files

	•	Human_Activity.html: Contains detailed analysis, visualizations, and results for the project.

🛠️ Requirements

To run the analysis, install the following Python packages:

pip install numpy pandas scipy matplotlib seaborn scikit-learn

Key Libraries

	•	numpy
	•	pandas
	•	scipy
	•	matplotlib
	•	seaborn
	•	scikit-learn

🚀 Usage

Steps to Run the Analysis

	1.	Load the Dataset: Start by loading the sensor data with pandas.
	2.	Preprocess and Reduce Dimensions: Use PCA to reduce the dimensionality from 561 columns to a manageable number of components.
	3.	Apply Clustering:
	•	K-means: Set up k clusters based on the PCA-transformed data.
	•	Hierarchical Clustering: Use Ward, single linkage, and complete linkage methods to form a hierarchical structure of clusters.
	4.	Visualize:
	•	Create scatter plots for the first two principal components with clusters.
	•	Generate dendrograms to show hierarchical clustering.

Visualizing Cluster Assignments

Use scatter plots to observe the clustering structure and dendrograms to examine hierarchical relationships between activities.

🔍 Key Insights

	•	PCA Effectiveness: The first principal component alone captures 55% of the variance, allowing for efficient dimensionality reduction.
	•	Cluster Interpretability: Clustering reveals distinct groups of activities, with separability between activities such as “walking” and “standing.”
	•	Visualization Benefits: Scatter plots and dendrograms make it easy to interpret the clustering outcomes and assess model effectiveness.

📈 Results

	•	Dimensionality Reduction: PCA significantly reduced the feature space, retaining essential variance for clustering.
	•	Clustering: K-means and hierarchical clustering identified meaningful activity clusters, with Ward’s linkage providing compact clusters.

🔧 Future Improvements

	•	Experiment with advanced feature engineering to enhance model accuracy.
	•	Consider supervised machine learning methods (e.g., neural networks) for improved activity classification.
	•	Explore additional clustering techniques like DBSCAN for better handling of noise in sensor data.

📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

🙋‍♂️ Contact

For questions or feedback, please reach out via GitHub Issues.
