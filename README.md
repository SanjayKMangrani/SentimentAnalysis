# Sentiment Analysis Application

## Overview
This project utilizes **embedded Watson AI libraries** to create a **sentiment analysis application** that can analyze provided text and determine its sentiment. The application is then deployed on the web using the **Flask framework**.

## Features
With the completion of this project, the following functionalities are implemented:

- **AI-based Sentiment Analysis**: Utilizes Watson NLP embedded libraries to analyze the sentiment of the given text.
- **Formatted Output**: Extracts and presents relevant information from Watson NLP responses.
- **Package Importability**: The application is packaged so it can be imported into any Python project.
- **Unit Testing**: Validates the accuracy of sentiment analysis outputs through unit tests.
- **Flask Deployment**: Deploys the application as a web-based service.
- **Error Handling**: Handles server errors gracefully, providing appropriate responses for HTTP 500 errors.
- **PEP8 Compliance**: Ensures adherence to Python's PEP8 coding guidelines through static code analysis.

## Technologies Used
- **Watson NLP**
- **Flask**
- **Python**
- **Unit Testing (unittest/pytest)**
- **Static Code Analysis (flake8, pylint)**

## Installation & Usage
### Prerequisites
Ensure you have **Python 3.x** installed along with the required dependencies.

### Installation Steps
1. Clone this repository:
   ```sh
   git clone https://github.com/SanjayKMangrani/SentimentAnalysis.git
   cd your-repo
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

### Running the Application
Start the Flask server:
```sh
python app.py
```
The application will be available at `http://localhost:5000/`.

### Running Tests
Execute unit tests:
```sh
pytest tests/
```

## Contributing
Feel free to fork this repository, make improvements, and submit a pull request!

---
Developed with ❤️ using **Watson AI & Flask**.
