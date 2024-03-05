# Bite Buddy

## Description

Bite Buddy is a web application that helps users find the total calories and macronutrient content of a meal. Users can take a picture of their meal and the application will use Google Gemini's API to identify the food items in the picture and will provide the nutritional information for each item as well as the total nutritional content of the meal.

## Deployment

Bite Buddy is deployed on Streamlit and can be accessed [here](https://slbitebuddy.streamlit.app/).

## Installation

To install Bite Buddy, you will need to have the following installed on your machine:
- Python 3.9+
- Streamlit 1.31.1
- Pillow 10.2.0
- Google GenerativeAI 0.4.0

To install these packages, run the following command in your terminal:

```bash
python -m pip install -r requirements.txt
```

## Technologies
- Python
- Streamlit
- Pillow
- Google GenerativeAI

## Usage

To use Bite Buddy, run the following command in your terminal:

```bash
streamlit run app.py
```

## Contributing

To contribute to Bite Buddy, please follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.