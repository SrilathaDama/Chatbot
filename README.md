# Advanced-Chatbot-with-Langchain-and-OpenAI

This project allows you to upload PDF documents, process them, and then engage in a conversational interface where you can ask questions about the documents.

## Getting Started

### Install Dependencies

`pip install -r requirements.txt`

**Architecture**
![image](https://github.com/SrilathaDama/Chatbot/assets/108073535/3cd1e350-1386-46cd-bd1c-459eb6a24674)

### How it Works
1. GUI Development: The application's graphical user interface (GUI) is built using Streamlit, providing an intuitive and user-friendly interface for document upload, processing, and chat interaction.
2. Document Processing: Upon document upload, the application reads text from PDF files and splits it into chunks for efficient processing.
3. Text Embeddings: OpenAIEmbeddings are utilized to generate embedding vectors from text chunks, which are then used to find the most relevant content to a user's question.
4. Conversational Retrieval Chain: A conversational retrieval chain is built using Langchain, incorporating the OpenAI model for context generation. This chain facilitates seamless conversation flow and response generation based on the content in the uploaded PDFs.

## How to Use

1. **Run the Streamlit App**
 `streamlit run app.py`
2. **Upload & Process Documents**
    - This GUI allows the user to upload PDF documents and process them to extract text and create a vector store for conversational retrieval.
3. **Chat**
    - Once the documents are processed, users can switch to the chat interface to start asking questions related to the uploaded documents.
    - Interact with the system by typing questions in the text input field and view bot responses in real-time.

## Technologies/Libraries/Tools Used
1. Streamlit: For building the application's graphical user interface.
2. Langchain: For building the conversational retrieval chain and context generation.
3. OpenAI: For generating responses based on the content in PDF documents.
4. PyPDF2: For extracting text from PDF documents.
5. Faiss: For creating and managing vector stores efficiently.
6. Python: The primary programming language used for development.

## Conclusion
The Advanced Chatbot project showcases the integration of advanced natural language processing techniques with document processing capabilities to create an intelligent conversational interface. By leveraging state-of-the-art technologies such as Langchain and OpenAI, users can seamlessly interact with PDF documents and receive accurate and informative responses to their questions. This project demonstrates the potential of AI-powered chatbots in enhancing document understanding and accessibility.
