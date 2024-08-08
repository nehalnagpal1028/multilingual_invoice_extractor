# multilingual_invoice_extractor

The Multilingual Invoice Extractor is a Streamlit web application that leverages Google Gemini Pro Vision to extract and interpret information from invoice images in multiple languages. The application allows users to upload an invoice image and provides detailed responses based on the content of the uploaded invoice.

Features
1. Multi-language support: Extracts information from invoices in various languages.
2. Easy to use: Simple and intuitive web interface.
3. Google Gemini Pro Vision: Utilizes advanced AI for content generation and image processing.
4. 
Setup and Installation
1. Prerequisites
2. Python 3.x
3. Streamlit library
4. Pillow library for image processing
5. google.generativeai library
6. A Google API key with access to Google Gemini Pro Vision

Installation

Clone the repository:
git clone https://github.com/your-username/multilingual_invoice_extractor.git

Navigate to the project directory:
cd multilingual_invoice_extractor

Create a virtual environment:
python -m venv venv

Activate the virtual environment:
On Windows:
.\venv\Scripts\activate
On macOS and Linux:
source venv/bin/activate

Install the required packages:
pip install -r requirements.txt

Create a .env file in the project directory and add your Google API key:
GOOGLE_API_KEY=your_google_api_key


Run the Streamlit application:
1. streamlit run app.py
2. Open your web browser and navigate to http://localhost:8501 to access the application.
3. Upload an invoice image (jpg, jpeg, png) using the file uploader.
4. Enter a prompt related to the invoice in the input field.
5. Click the "Tell me about the invoice" button to get the response.
