# Diabetes Prediction

## Demo Video

Watch the demo of the application here:  
[![Watch the demo](https://img.youtube.com/vi/WRmHlcUr0DE/0.jpg)](https://youtu.be/WRmHlcUr0DE)

## Overview

This project aims to predict the likelihood of diabetes in individuals using a dataset of health metrics. The application utilizes machine learning techniques to analyze the data and provide predictions, enhancing early detection and management of diabetes.

## Project Structure

```
.
├── .gitignore
├── LICENSE
├── README.md
├── app.py
├── backend.py
├── diabetes_prediction_dataset.csv
├── model1.ipynb
└── prediabetes.mp4
```

## Getting Started

### Prerequisites

- Python 3.x
- pip
- [Anaconda](https://www.anaconda.com/products/distribution) (recommended for package management)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv env_name
   source env_name/bin/activate  # On Windows use `env_name\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

1. **Start the Application**:
   Run the following command to start the Tkinter desktop application:
   ```bash
   python app.py
   ```

## Workflow

1. **Data Ingestion**:
   - The application ingests data from `diabetes_prediction_dataset.csv`.
   - This data contains various health metrics useful for predicting diabetes.

2. **Exploratory Data Analysis (EDA)**:
   - Use the Jupyter notebook `model1.ipynb` for exploratory data analysis.
   - Visualize trends, correlations, and key features influencing diabetes.

3. **Model Training**:
   - The trained model is built and evaluated within `model1.ipynb`.
   - Different algorithms can be tested to find the best fit for predictions.

4. **Application Logic**:
   - `app.py` contains the Tkinter application logic, providing a graphical user interface for user interaction.
   - `backend.py` manages the model predictions and data processing.

5. **User Interaction**:
   - Users can input health metrics through the Tkinter interface.
   - The model provides predictions based on the inputs and displays the results.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request to enhance the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the contributors and tools that facilitated the project, including libraries for machine learning and data visualization.
