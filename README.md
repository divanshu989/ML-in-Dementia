ML-in-Dementia - A Machine Learning Approach to Early Detection of Dementia
Overview
Dementia is a progressive neurodegenerative disorder that affects millions worldwide, leading to memory loss, cognitive decline, and impaired daily functioning. Early detection is crucial for effective management and intervention. This project leverages machine learning techniques to analyze clinical and imaging data, aiming to predict the onset of dementia in individuals.

Features
•	Data Preprocessing: Cleaning and normalization of datasets to handle missing values and outliers.
•	Feature Engineering: Extraction and selection of relevant features from clinical and imaging data.
•	Model Development: Implementation of various machine learning algorithms to predict dementia.
•	Evaluation Metrics: Assessment of model performance using accuracy, precision, recall, and F1-score.
•	Visualization: Graphical representation of data distributions and model outcomes.

Dataset
The project utilizes data from the Open Access Series of Imaging Studies (OASIS), which provides cross-sectional MRI data along with demographic and clinical information of subjects aged 60 to 96.

Key variables include:
•	Age: Age of the subject.
•	Gender: Male or Female.
•	EDUC: Years of education.
•	SES: Socioeconomic status.
•	MMSE: Mini-Mental State Examination score.
•	CDR: Clinical Dementia Rating.
•	eTIV: Estimated Total Intracranial Volume.
•	nWBV: Normalized Whole Brain Volume.
•	ASF: Atlas Scaling Factor.

Methodology
1.	Data Acquisition: Retrieval of the OASIS dataset and initial exploration.
2.	Preprocessing: Handling missing values, encoding categorical variables, and normalizing numerical features.
3.	Feature Selection: Identifying the most significant features contributing to dementia prediction.
4.	Model Training: Applying algorithms such as Logistic Regression, Decision Trees, Random Forest, and Support Vector Machines.
5.	Model Evaluation: Using cross-validation and performance metrics to assess model accuracy and reliability.
6.	Visualization: Creating plots to understand data distributions and model predictions.

Results
The machine learning models demonstrated varying degrees of accuracy, with ensemble methods like Random Forest showing promising results in predicting dementia. The evaluation metrics indicated the models' potential in assisting early diagnosis, which could be instrumental in clinical settings.

Installation
1.	Clone the Repository:
2.	git clone https://github.com/divanshu989/ML-in-Dementia.git
3.	Navigate to the Project Directory: cd ML-in-Dementia
5.	Install Required Packages: Ensure you have Python installed. Then, install the necessary libraries: pip install -r requirements.txt

Usage
After installation, you can run the main script to train and evaluate the models:
python main.py

Ensure that the dataset is placed in the appropriate directory as specified in the script.

Contributing
Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
•	The OASIS project for providing access to valuable neuroimaging datasets.
•	Open-source contributors and the machine learning community for continuous support and resources.
