# **Quiz Generator**
This project is a Streamlit application that is designed to generate quizes on inputted topics from user-uploaded PDF files. It uses document processing, text embedding, and Goole Gemini.

## **Features**
- *Document Ingestion*: Upload PDFs to be used as the source of the quiz material.
- *Quiz Generation*: Automatically generate a quiz with a certain number of questions based on the uploaded material.
- *Question Navigation*: Navigate through previous/next generated quesitons of the quiz.

## **Installation**
1. Clone the repository
2. Install the dependencies in 'requirements.txt'
3. Set up Google Cloud Vertex AI and input project ID in the "embed_config"

## **Usage**
1. Run the Streamlit app
2. Use the interface
    - Upload PDFs
    - Set topic of quiz
    - Choose the number of questions to generate
    - Generate quiz