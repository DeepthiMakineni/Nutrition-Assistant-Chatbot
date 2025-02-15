# Nutrition-Assistant-Chatbot


About the Project 

The Nutrition Assistant Chatbot is an AI-powered chatbot that helps users with dietary recommendations, nutritional facts, and meal planning based on their preferences and health goals. It leverages LangChain, OpenAI GPT, Flask, and Pinecone to deliver accurate and interactive responses.

How to Run?

#STEP 1: Clone the Repository

git clone https://github.com/DeepthiMakineni/Nutrition-Assistant-Chatbot.git

cd Nutrition-Assistant-Chatbot

#STEP 2: Create a Conda Environment

conda create -n nutrition-chatbot python=3.10 -y
conda activate nutrition-chatbot

#STEP 3: Install Dependencies

pip install -r requirements.txt

#STEP 4: Set Up Environment Variables

Create a .env file in the root directory and add your API credentials:

PINECONE_API_KEY = "your_pinecone_api_key"

OPENAI_API_KEY = "your_openai_api_key"

#STEP 5: Run the Indexing Script

Store embeddings into Pinecone:

python store_index.py

#STEP 6: Start the Chatbot

python app.py


Finally,open your browser and navigate to: localhost:6060

### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone
