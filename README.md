# Nutrition-App-Using-Gemini-Pro-



## Overview

The **Nutrition App Using Gemini Pro** is a sophisticated web application that provides detailed nutritional analysis of food items from uploaded images. Utilizing the advanced capabilities of the Gemini Pro AI model, this application accurately identifies food items and calculates their calorie content based on user inputs.

## Features

- **Image Upload**: Upload food images for analysis.
- **Nutritional Insights**: Get detailed information about the food items, including calorie counts.
- **Custom Prompts**: Enter specific prompts for tailored nutritional analysis.
- **Real-time Feedback**: Instant results and detailed breakdowns.

## Technologies

- **Frontend**: [Streamlit](https://streamlit.io/) – for creating interactive web applications.
- **Backend**: Python – the core language for processing and analysis.
- **AI Model**: [Gemini Pro (Gemini-1.5-Flash)](https://gemini.google.com/) – for image analysis and nutritional insights.
- **Image Processing**: [Pillow (PIL)](https://python-pillow.org/) – for handling image uploads and processing.

## Installation

### Prerequisites

- Python 3.7 or later
- API key for Gemini Pro
- Required Python packages

### Setup

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/Nutrition-App-Using-Gemini-Pro.git
    ```

2. **Navigate to Project Directory**

    ```bash
    cd Nutrition-App-Using-Gemini-Pro
    ```

3. **Install Dependencies**

    Create a virtual environment and install the required packages:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

4. **Configure Environment Variables**

    Create a `.env` file in the project root and add your API key:

    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

## Running the Application

1. **Start the Streamlit Server**

    ```bash
    streamlit run app.py
    ```

2. **Access the Application**

    Open your web browser and go to the URL provided by Streamlit to interact with the application.

## Usage

1. **Input Prompt**: Provide a description of the food items in the text input field.
2. **Upload Image**: Select and upload an image of the food items.
3. **Submit**: Click the "Tell me the total calories" button to receive nutritional analysis.


## Image

Here is a screenshot of the application:

![Nutrition App Screenshot](https://miro.medium.com/v2/resize:fit:1400/1*5uNikb66besce6vEASR3bQ.png)

## Contributing

Contributions are welcome! Please submit issues or pull requests for enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Streamlit](https://streamlit.io/) for enabling rapid development of web applications.
- [Gemini Pro](https://gemini.google.com/) for providing advanced AI capabilities.
- [Pillow (PIL)](https://python-pillow.org/) for image manipulation support.

