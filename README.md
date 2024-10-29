
# Invoice Q&A Chatbot with Gemini AI

## Description

This project is a Q&A chatbot application built using **Streamlit** and **Google Generative AI**'s Gemini model. Designed to process and analyze uploaded invoice images, the chatbot allows users to ask questions about invoice details and receive AI-generated responses. By leveraging the **Gemini 1.5 Flash** model, the application provides insightful answers based on the invoice data in real-time, making it a useful tool for automating document processing and understanding.

<img width="438" alt="Screenshot 2024-10-29 at 7 00 04 PM" src="https://github.com/user-attachments/assets/97628c11-b278-420f-b5ac-e6991c26d88e">

## Features

- **Image Upload**: Users can upload invoice images in JPG, JPEG, or PNG formats.
- **AI-Powered Q&A**: The chatbot uses the Gemini 1.5 Flash model to interpret invoice images and generate responses.
- **User-Friendly Interface**: Built with Streamlit, the application offers a straightforward interface with text input and image display options.
- **Dynamic Analysis**: After uploading an invoice, users can input specific questions to get precise answers about the image's content.

## How It Works

1. **Upload an Invoice**: Users upload an invoice image to the app.
2. **Ask a Question**: A question prompt is provided where users can enter inquiries related to the uploaded invoice.
3. **AI Response**: The application processes the image and the user's question, then generates a response using the Gemini model, focusing on invoice-specific data.

## Setup and Installation

1. Clone the repository.
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root directory and add your Google API key:
   ```plaintext
   GOOGLE_API_KEY=your_api_key
   ```
4. Run the application with:
   ```bash
   streamlit run app.py
   ```

## Requirements

- **Streamlit** for the web interface
- **google-generativeai** to access the Gemini model
- **python-dotenv** for environment variable management
- **Pillow (PIL)** to handle image processing

## Future Enhancements

- Support for additional document types beyond invoices.
- Enhanced natural language understanding for more complex queries.
- Integration with other generative AI models for broader functionality.

## Acknowledgments

Thanks to Google for providing access to the Gemini model and Streamlit for their powerful, user-friendly web app framework. This project aims to simplify document processing tasks through AI-driven insights.
