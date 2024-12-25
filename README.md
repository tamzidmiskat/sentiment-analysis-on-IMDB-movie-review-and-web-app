# Sentiment Analysis Model Testing and Web Application

This project showcases the testing and deployment of a pre-trained sentiment analysis model. The model is integrated with a web application for real-time sentiment predictions.

## Project Overview
The notebook demonstrates:
- Loading a pre-trained sentiment analysis model and tokenizer.
- Testing the model with sample reviews to evaluate its predictions.
- Deploying the model as a web application using Gradio for interactive use.

## Features
- **Model Testing**: Tests the pre-trained model on sample reviews to predict sentiments as "positive" or "negative."
- **Interactive Web Application**: A Gradio-based application allowing users to input text and get real-time sentiment predictions.
- **Pre-trained Model Utilization**: Leverages a pre-trained deep learning model (`model.h5`) and tokenizer for efficient prediction.

## File Structure
```
root
├── model/                    # Directory containing pre-trained model and tokenizer (to be added by user)
├── Sentiment_Model_Testing_and_Web_Applictaion.ipynb # Main Jupyter Notebook
├── requirements.txt          # List of dependencies
└── README.md                 # Project documentation
```

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```
2. Install necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Add the pre-trained model (`model.h5`) and tokenizer (`tokenizer.pkl`) to the `model/` directory.
2. Open `Sentiment_Model_Testing_and_Web_Applictaion.ipynb` in Jupyter Notebook or a similar environment.
3. Execute the cells to:
   - Load the model and tokenizer.
   - Test the model with sample reviews.
   - Launch the Gradio web application.

4. Access the web application using the generated Gradio link.

## Dependencies
- Python 3.x
- TensorFlow / Keras
- Gradio
- NumPy
- Joblib

## Example Results
- **Sample Prediction**: "Exciting plot, mediocre character development" -> Sentiment: Positive
- **Web Application**: Accessible via Gradio, allowing user interaction with the model.

## Future Enhancements
- Improve the model's accuracy with additional training data.
- Enhance the user interface of the web application.
- Deploy the application on a public server for broader access.

