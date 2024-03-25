## Chat With Multiple PDFs Using Gemini

This project allows you to chat with multiple PDF files using the Google Generative AI model Gemini. You can upload your PDF files, ask questions related to the content of the PDFs, and get answers based on the information in the PDFs.

## App Link
https://chat-withyour-pdf-raushan.streamlit.app/

## Usage

    1. Upload your PDF files using the file uploader.
    2. Ask a question related to the uploaded PDF files.
    3. Click on the "Submit & Process" button to process the PDF files and get the answer to your question.

![image](https://github.com/raushan9jnv/Gemini-Pro-LLM-MultiplePDF-Chat/assets/86125144/68854cdd-ff35-4684-8a43-e12b17ae25e0)


    
## Tools and Libraries Used

- **Streamlit**: Used for building the web application interface, making it easy to create interactive elements and display information to the user.
- **PyPDF2**: Used for reading text from PDF files, allowing the app to extract information from uploaded PDFs.
- **Langchain**: A library for natural language processing tasks, used for text splitting, vector embeddings, and question answering.
- **Google Generative AI**: Specifically, the Gemini model, used for generating answers to questions based on the content of the PDF files.
- **FAISS**: A library for similarity search, used for creating a vector store of text chunks from the PDF files to enable efficient search for relevant information.
- **dotenv**: Used for loading environment variables, allowing the app to securely access the Google Generative AI API key.

## How It Works

1. **Upload PDF Files**: You can upload multiple PDF files containing the information you want to query.

2. **Process PDF Files**: Once you upload the PDF files, the app extracts the text from the PDFs and splits it into chunks. These chunks are used to create a vector store, which is used for similarity search during question answering.

3. **Ask Questions**: You can then ask questions related to the content of the PDF files. The app uses the Gemini model to find the most relevant chunks from the PDFs and generates an answer based on the context provided in the question.

4. **Get Answers**: The app displays the answer generated by the Gemini model based on the information in the PDF files.

# Clone and Make Yours :)

## Create Virtual Env
- pip install virtualenv
- virtualenv venv
- **On Windows:** venv\Scripts\activate
- **On MacOS/Linux:** source venv/bin/activate

## Installation

    1. Clone the repository:
        ```
        git clone https://github.com/raushan9jnv/Gemini-Pro-LLM-MultiplePDF-Chat.git
        ```

    2. Install the required libraries:
        ```
        pip install -r requirements.txt
        ```

## How to Run

    1. Navigate to the project directory:
        ```
        cd path-to-cloned-directory
        ```

    2. Run the Streamlit app:
        ```
        streamlit run app.py
        ```
## Author

    Raushan Kumar
Thanks

   

 





