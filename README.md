# Dosha Prediction Application

This is a Streamlit application that helps predict an individual's Ayurvedic dosha based on their physical and behavioral characteristics. The application presents a series of multiple-choice questions, and based on the user's responses, it predicts their dominant dosha(s) using a pre-trained TensorFlow model.

## Prerequisites

Before running the application, make sure you have the following dependencies installed:

- Python 3.x
- Pip (Python package installer)

## Installation

1. Clone the repository or download the source code.
2. Navigate to the project directory in your terminal or command prompt.
3. Create a new virtual environment (optional but recommended):

```
$ python -m venv env
```

4. Activate the virtual environment:

   - On Windows:
   ```
   $ env\Scripts\activate
   ```

   - On Linux/macOS:
   ```
   $ source env/bin/activate
   ```

5. Install the required packages by running:

```
$ pip install -r requirements.txt
```

## Usage

1. Make sure your virtual environment is activated (if you created one).
2. Run the Streamlit application with the following command:

```
$ streamlit run app.py
```

3. The application will open in your default web browser. If not, you can access it by clicking the URL provided in the terminal.
4. Send a "Hi!" message to the bot.
5. Answer all the questions by entering the option number.
5. Once you have answered all the questions, the application will predict your dominant dosha(s) based on your responses.

