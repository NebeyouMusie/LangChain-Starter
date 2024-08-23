# LangChain Starter
- a starter repo on how to create your first simple LLM application using LangChain.

## Description
- In this project I've built a streamlit web app that leverages the LLAMA3.1 LLM to create an AI-powered blog content. 
- The tool assists users in generating blog titles and content based on provided inputs.

![AI Blog Assistant UI Image](./images/ai-blog-assistant-ui.png)

## DEMO
- You can check the live demo [here](https://8505-01j0bv4h1g771v2shtqjfpr66t.cloudspaces.litng.ai/)

## Libraries Used
 - streamlit
 - langchain
 - python-dotenv
 - langchain_community
 - langchain_huggingface
 - langchain_groq

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: `git clone https://github.com/NebeyouMusie/AI-Blog-Assistant.git`
 3. Create and Activate Virtual Environment (Recommended)
    - `python -m venv venv`
    - `source venv/bin/activate` for Mac and `venv/bin/activate` for Windows
 4. Navigate to the projects directory `cd ./AI-Blog-Assistant` using your terminal
 5. Install Libraries: `pip install -r requirements.txt`
 6. Enter your `GROQ_API_KEY` in the `.env.example` file then change the file to `.env`. You can get your `GROQ_API_KEY` from [here](https://console.groq.com/keys)
 7. run `streamlit run app/app.py`
 8. open the link displayed in the terminal on your preferred browser

 ## Usage
 #### a. Title Generation
 - Enter a topic and target audience in the "Input the topic" expander.
 - Click the "Submit the topic" button to generate a list of potential titles.

 #### b. Blog Generation
 - Enter the desired blog title in the "Input Blog Details" expander.
 - Set the desired word length using the number input.
 - Add keywords by entering them in the input field and clicking "Add Keyword".
 - Click the "Submit the Info" button to generate the blog content.

## Collaboration
- Collaborations are welcomed ❤️

## Acknowledgments
 - I would like to thank [UNLEASHING TOMORROW'S {TECH}](https://www.youtube.com/@UNLEASHINGTOMORROWSTECH)
   
## Contact
 - LinkedIn: [Nebeyou Musie](https://www.linkedin.com/in/nebeyou-musie)
 - Gmail: nebeyoumusie@gmail.com
 - Telegram: [Nebeyou Musie](https://t.me/NebeyouMusie)