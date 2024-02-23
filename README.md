# AI Fitness Trainer

The AI Fitness Trainer is a Streamlit web application that provides personalized workout and diet plans based on user input. It utilizes a language model to generate tailored recommendations for achieving fitness goals such as weight loss or weight gain.


## About the Model

The language model used in this project is the LangChain framework, powered by CTransformers. It generates responses based on predefined templates and input variables.


## Features

- Personalized workout plans
- Customized diet plans
- BMI calculation
- Goal-specific recommendations

## Setup

1. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Download the pre-trained language model (`llama-2-13b-chat.ggmlv3.q4_0.bin`) and place it in the project directory.

## Usage

1. Run the Streamlit application:

    ```bash
    streamlit run fitness.py
    ```


2. Enter your profile information in the sidebar (name, age, weight, height, gender, fitness goal, and time period).

3. Click on the "Get Recommendations" button to generate personalized workout and diet plans.

4. View the generated plans along with BMI information and total workout time.

## Screenshots

![Screenshot 2024-02-21 220256](https://github.com/Shobika-k2004/AI-Fitness/assets/94346032/a03de3a1-9fd9-4fe0-b8ea-ebde3a278f15)




