# Heart-Disease-Classification-Model
This project is a machine learning model designed to classify whether a patient is likely to have heart disease based on various health metrics. The goal is to aid in early diagnosis and improve preventive measures for heart disease.

## Features
1.Data Preprocessing: Handling missing values, normalization, and feature selection.

2.Model Training: Using various classification algorithms to train the model.

3.Model Evaluation: Assessing the model's performance using metrics like accuracy, precision, recall, and F1-score.

4.Visualization: Graphical representation of data distribution and model performance.

5.Deployment: Deploying the model using a web interface for real-time predictions.

## Technologies Used
Programming Language: Python

### Libraries:

Data Analysis: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn

Jupyter Notebook: For interactive data analysis and model training

Flask: For deploying the model as a web application

## Installation
To set up the Heart-Disease-Classification-Model on your local machine, follow these steps:

Clone the repository:

      git clone https://github.com/rahul-200/Heart-Disease-Classification-Model.git
      cd Heart-Disease-Classification-Model
      
Create a virtual environment:

         python -m venv venv
Activate the virtual environment:

On Windows:

    venv\Scripts\activate

On macOS/Linux:

      source venv/bin/activate

Install dependencies:

     pip install -r requirements.txt
     
Run the Jupyter Notebook:

     jupyter notebook

Start the Flask web application:

     python app.py

Open your browser and go to http://127.0.0.1:5000 to access the web interface.

## Usage
1.Data Preprocessing: Load the dataset and perform preprocessing steps such as handling missing values, normalization, and feature selection. This is demonstrated in the Jupyter Notebook provided.

2.Model Training: Train various classification models using the preprocessed data. The notebook includes code for training models like Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine.

3.Model Evaluation: Evaluate the trained models using metrics like accuracy, precision, recall, and F1-score. The notebook provides detailed visualizations and evaluation metrics for each model.

4.Prediction: Use the trained model to make predictions on new data. The Flask web application allows users to input health metrics and get real-time predictions on the likelihood of having heart disease.

## Contributing
We welcome contributions from the community to improve the Car-Selling-Portal. If you find any bugs or have suggestions for new features, please feel free to open an issue or submit a pull request.

### Steps to Contribute
1.Fork the repository on GitHub.

2.Create a new branch for your feature or bug fix:
         
         git checkout -b feature-branch

3.Make your changes and commit them with a descriptive message:

      git commit -m "Description of your changes"

4.Push your changes to your forked repository:

      git push origin feature-branch

5.Create a Pull Request to the main repository. Provide a detailed description of your changes and the problem or feature they address.

## Contact
If you have any questions or need further assistance, feel free to contact me:

Email: nagarahul2004@gmail.com

GitHub: rahul-200
