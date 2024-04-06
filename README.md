# Streamlit-Chatbot-Interface

This project helps you engage in insightful conversations and get prompt assistance. Powered by OpenAI's GPT-3.5 Turbo model, Intellecta is designed to provide intelligent responses to your queries.

## How to use

1. Clone this repo
     git repo https://github.com/dishathakurata/Streamlit-Chatbot-Interface.git
   
2. Create a new venv or conda environment
      Using venv:
        bash
        python -m venv venv
        source venv/bin/activate
   
      Using conda:
        bash
        conda create --name myenv
        conda activate myenv

3. Install Streamlit
      pip install streamlit openai python-dotenv

   Install Required Modules
      pip install -r requirements.txt


4. Test installation
      streamlit hello

5. Renave example.env file to .env
      mv renamedot.env .env

6. Run your Streamlit app with
      streamlit run app.py
