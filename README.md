# LangChain Starter
- a starter repo on how to create your first simple LLM application using LangChain.
- You can check out the complete explanation from the Langchain Documentation [here](https://python.langchain.com/v0.2/docs/tutorials/llm_chain/)

## Libraries Used
 - langchain
 - langchain-groq
 - python-dotenv
 - fastapi

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: `git clone https://github.com/NebeyouMusie/LangChain-Starter.git`
 3. Create and Activate Virtual Environment (Recommended)
    - `python -m venv venv`
    - `source venv/bin/activate` for Mac and `venv/bin/activate` for Windows
 4. Navigate to the projects directory `cd ./LangChain-Starter` using your terminal
 5. Install Libraries: `pip install -r requirements.txt`
 6. Enter your `GROQ_API_KEY` and `LANGCHAIN_API_KEY` in the `example.env` file then change the file to `.env`. You can get your `GROQ_API_KEY` from [here](https://console.groq.com/keys) and your `LANGCHAIN_API_KEY` from [here](https://smith.langchain.com/) in the settings page.
 7. run `python serve.py` then, we should see our chain being served at http://localhost:8000
 8. run `python client.py` you'll see a response in your terminal 

## Collaboration
- Collaborations are welcomed ❤️

## Acknowledgments
 - I would like to thank [LangChain](https://python.langchain.com/)
   
## Contact
 - LinkedIn: [Nebeyou Musie](https://www.linkedin.com/in/nebeyou-musie)
 - Gmail: nebeyoumusie@gmail.com
 - Telegram: [Nebeyou Musie](https://t.me/NebeyouMusie)