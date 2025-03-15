## RAG with Stable Diffusion

A RAG database containing news and performance information around NFL football players was integrated with a generative AI model that a user can ask football-related questions and receive contextual information along
with a AI-generated image through stable diffusion. A Streamlit application was included to deploy the model to users over the web.

## Features
1. Image and Video Scene Description
2. Question Answering
3. Interactive web application using Streamlit

## Requirements
Python 3.8+

Install required libraries:
```
!pip install diffusers transformers accelerate sentence-transformers faiss-cpu streamlit flask
```

## Usage
1. Clone the repository into Google CoLab
```
https://github.com/your_username/MultiModal-AI-App.git
```
2. Upload code to Google Colab
3. Run the Streamlit application
```
1. Press Ctrl-F9 to run application from Google Colab.
2. Copy the IP address listed after cell 3.
3. Click the link provided after cell 4.
```
4. The application will automatically open in your browser
```
Paste the IP address into the password field and the application will run.
```
5. Alternate option
```
1. Save the file to the current working directory as your_app.py.
2. Run the application via the terminal using the command:
    streamlit run your_app.py
```
Application demonstration video:
https://umsystem.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=60c16e68-54c0-4763-9bf1-b293001b5f30

Jupyter notebook link:
https://colab.research.google.com/drive/1HTXiWRAhBNIzwMQeoQwasYznkddr2BuP?usp=sharing 
