# Chat with PDF using Gemini

# 💬📄

This is a ChatBot integrated with a PDF text extraction feature, allowing for users to ask questions related to the uploaded PDF Documents. It leverages Google Generative AI models for conversational responses and FAISS(Facebook AI Similarity Search) for efficient text similarity search. The PDF files can range from school work PDF to lengthy PDFs that are too wordy to go through. The Chatbot will concisely extract needed information and give it as output.

## Features

* **PDF Text Extraction**: Upload PDF files to extract text for the ChatBot input.
* **Conversational Chatbot**: Ask questions from the extracted text and receive detailed and comprehensive answers.
* **Gemini-Pro Model**: Utilizies Gemini-Pro Model for conversational responses with contextual understanding.
* **FAISS Vector Store**: Generates vector embeddings for efficient similarity search of documents.
* **Streamlit UI**: Interactive UI built with Streamlit for easy usage.

## Getting Started

1. To run the chatbot locally on your machine, clone the repository to your local machine:

   git clone https://github.com/KoriMigan/ChatBot_Development.git
   cd ChatBot_Development
2. Install the required dependencies:

   pip install -r requirements.txt
3. Set up environment variables:

   Create a '.env' file in the project directory and add your Google API key:

   Google_api_key=YOUR_GOOGLE_API_KEY_HERE
4. Run the application:

   streamlit run app.py
5. Use the Streamlit UI to upload PDF files, ask questions and feel free to interact with the chatbot.

## Dependencies

* Streamlit
* PyPDF2
* LangChain(langchain, langchain_google_genai)
* FAISS(vectorstores)
* Google Generative AI(google.generativeai)

## File Structure

* 'app.py': Main application file containing Stramlit UI and backend logic for the chatbot.
* 'readme.md': Project documentation.
* 'venv': Environment variables file.
* 'requirements.text': List of Python dependencies.

## Contribution

Contributions are welcome! If you encounter any issues or have suggestions for improvement, please create a GitHub issue or submit a pull request.

## License

This Project is licensed under the MIT License - see the 'LICENSE' file for details.
