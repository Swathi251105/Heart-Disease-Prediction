
# Heart Disease Prediction

## Project Overview
This project is a web-based application that predicts the probability of heart disease based on user inputs such as age, cholesterol levels, and resting blood pressure. It utilizes machine learning techniques to make predictions and is built using Flask for the backend and HTML/CSS for the frontend.

## Technologies Used
- Python
- Flask
- Pandas
- NumPy
- Scikit-learn (Logistic Regression)
- HTML/CSS

## Dataset
The dataset used for training the model is `heart.csv`, which contains relevant medical data for heart disease prediction. The dataset includes the following features:
- Age
- Resting Blood Pressure (trtbps)
- Cholesterol (chol)
- Target Output (0: No Heart Disease, 1: Heart Disease)

## Project Structure
```
Heart Disease Prediction/
│── static/
│── templates/
│   ├── heartDiseaseForm.html
│── heart.csv
│── main.py
│── README.md
```
- `main.py`: Contains the Flask backend logic, loads the dataset, trains the model, and handles user input.
- `heartDiseaseForm.html`: Frontend form for user input.
- `heart.csv`: Dataset used for training and prediction.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/Swathi251105/Heart-Disease-Prediction.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Heart-Disease-Prediction
   ```
3. Install required dependencies:
   ```sh
   pip install flask numpy pandas scikit-learn
   ```
4. Run the application:
   ```sh
   python main.py
   ```
5. Open your browser and go to `http://127.0.0.1:5000/`.

## Usage
1. Enter your age, cholesterol level, and resting blood pressure.
2. Click on the "Predict Probability" button.
3. The model will analyze the input and display the prediction result.

## Contributing
Feel free to submit pull requests or issues to improve the project.

## License
This project is open-source and available under the MIT License.

