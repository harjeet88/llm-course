# Setup for Course
We will set up following 
1. API key for OPENAI to use OPEN AI Models
2. API key for Google/Gemini to use google's LLM models
3. API Key and account set up for Hugging face
4. Setup Ollama
5. Setup Gogle Collab

# Google collab set up
1. Visit: https://colab.research.google.com or open this notebook in google collab - https://github.com/harjeet88/llm-course/blob/main/empty_notebook.ipynb 
2. You are Ready :)

## API Key for Open AI
1. Go to: https://platform.openai.com/signup and signup
2. Navigate to: https://platform.openai.com/account/api-keys
3. Click “+ Create new secret key”
4. Name your key (e.g., my-dev-key)
5. Copy the key immediately and store it securely – you won't be able to view it again!

## Get Gemini API Key
1. Go to : https://aistudio.google.com/apikey and sign up
2. click "+ Create API key"
3. Copy key and store somewhere(prefer google collab key store) as you will not be able to view it again

## Huggingface account
1. Go to: https://huggingface.co/join
2. Sign up using:
     Email + password or GitHub / Google account
3. Navigate to: https://huggingface.co/settings/tokens fill details and generate token
4. Copy and store it securely — you won’t be able to view it again!

## Ollama setup
1. Open terminal and run following commands
2. !curl -fsSL https://ollama.com/install.sh | sh
3. ollama serve # this will start ollama server
in another terminal run following
4. ollama pull llama3.2:1b #this will download open source model llama 3.2 with 1b parameters
5. pip install ollama # this will install ollama for using with python
6. Refer - https://github.com/harjeet88/LLM_experiemnts/blob/main/Setup_ollama.ipynb
   

