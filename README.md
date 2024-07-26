# End-to-End-LLM-and-Large-image-model-Application-using-Gemini-Pro-Vision
![image](https://github.com/user-attachments/assets/a305bae2-1309-49d0-85d1-2cf7916d3a6c)
Overview:

Welcome to my latest project, an end-to-end application utilizing Google's Gemini Pro Vision model. This Streamlit web application is designed to analyze and describe images, demonstrating the power and versatility of the Gemini Pro Vision model.

About This Project

This project leverages the capabilities of Google's Gemini Pro Vision model through a user-friendly Streamlit interface. The application allows users to input text prompts and upload images, which the model then analyzes to generate descriptive content.

Key Features:

1.Text and Image Input: Users can provide text prompts and upload images in JPG, JPEG, or PNG formats.

2.Model Response: The application sends the input text and image to the Gemini Pro Vision model, which returns a detailed description.

3.Interactive Interface: A simple and interactive user interface built with Streamlit, ensuring a smooth user experience.
![image](https://github.com/user-attachments/assets/22042238-b8d9-4009-81a6-b7e98522e7d4)

How It Works

1. Setup and Configuration:
>Environment variables are loaded using dotenv.
>Libraries such as streamlit, os, google.generativeai, and PIL are imported.
>The Gemini model is configured with an API key.

2. Functionality:
>The get_gemini_response function processes the input and image, sending them to the model to retrieve the generated response.

3. Streamlit Application:
>The page is set up with a title and header.
>Users can input text prompts and upload images, which are displayed on the page.
>Upon clicking the submit button, the model's response is fetched and displayed.
