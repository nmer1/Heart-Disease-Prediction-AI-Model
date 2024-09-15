# Heart Disease Prediction Project

In this project, I used different machine learning models like Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest to predict heart disease. After trying several models, **Logistic Regression** gave the best accuracy of **88%**.

### How to Use

1. Clone this repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook file to train the model and evaluate it.

### Dataset

The dataset used for this project is included in the repository under the `data/` folder. To load the dataset in the Jupyter notebook, make sure to reference the correct file path:

```python
df = pd.read_csv('data/your_file.csv')

