# Blog_Generator
An AI-powered Blog Generator built with Python, Streamlit, LangChain, and Google Gemini API. Generate high-quality blogs with customizable tone, length, audience, and creativity using Gemini 2.5 Flash.

🚀 Features
Generate blogs on any topic
Choose different writing tones (Professional, Friendly, Technical, Funny, Motivational)
Select blog length (Short, Medium, Long)
Customize the target audience
Adjust AI creativity using the temperature slider
Simple and interactive Streamlit interface
Fast content generation with Google Gemini AI

🛠️ Tech Stack
Python
Streamlit
LangChain
Google Gemini API
python-dotenv

📂 Project Structure
BLOG_GENERATOR/
│── app.py
│── blog_generator.py
│── prompt.py
│── utils.py
│── .env
│── requirements.txt

⚙️ Installation
pip install -r requirements.txt

Create a .env file:

GOOGLE_API_KEY=YOUR_GEMINI_API_KEY

Run the application:

streamlit run app.py
📸 Demo

Generate AI-powered blogs by entering:

Topic
Tone
Length
Audience
Temperature

and click Generate Blog to instantly create a well-structured blog post.
