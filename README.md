![Forks](https://img.shields.io/badge/forks-0-blue)
![Stars](https://img.shields.io/badge/stars-0-yellow)

# PDF-GPT

## Description
In this project, a chatbot has been created for any pdf file using Flask, a popular web framework, and the Langchain, another popular framework for working wtih Large Language Models (LLMs). The developed chatbot will not just interact with users via text but also comprehend and answer questions related to the content of a specific document (PDF). The web-app is user-friendly in which simply upload a PDF file that you wish to analyse and summarize. Thus, we can ask any related question in the designated chatbox. 

## Tech Stack
PDF-GPT uses the following technologies:
- Flask
- Langchain
- HTML - CSS - Javascript

### Requirements
GitPython needs the `git` executable to be installed on the system and available in your `PATH` for most operations.
If it is not in your `PATH`, you can help GitPython find it by setting
the `GIT_PYTHON_GIT_EXECUTABLE=<path/to/git>` environment variable.

- Git (1.7.x or newer)
- Python >= 3.7

The list of dependencies are listed in `./requirements.txt`.

The installer takes care of installing them for you.

## Install and Clone

GitPython and its required package dependencies can be installed as below: 

`pip3 install virtualenv`

`virtualenv my_env` # create a virtual environment my_env

`source my_env/bin/activate` # activate my_env


Run the following commands to receive the project, and rename it to proper name, and finally move into that directory by running followings:

`git clone https://github.com/LimKimHoong/PDF-GPT.git`

`mv PDF-GPT build_chatbot_for_your_data`

`cd build_chatbot_for_your_data`

installing the requirements for the project :

`pip install Flask Flask_Cors langchain openai pdf2image chromadb pypdf tiktoken`

## API Connect
In `worker.py`, initialize OpenAI’s HTTP request library using your own API key that you set up earlier (or get one from here) by replacing `api_key="YOUR API KEY"` with your API key. Save and close the file.

## Run the web-app
To quickly run the chatbot, we need to run the `server.py` file, by the following code in the terminal: 

`python3 server.py`

Then, open the browser and copy the running url (Ex: `http://127.0.0.1:8000` ). 

## Stop the web-app 
Once you’ve had a chance to run and play around with the application, please press `Crtl` (a.k.a. control (^) for Mac) and `C` at the same time to stop the container and continue the project (as it is also mentioned in terminal).

## Contributing
Welcome any and all contributions! Here are some ways you can get started:
1. Report bugs: If you encounter any bugs, please let me know. Open up an issue and let me know the problem.
2. Contribute code: If you are a developer and want to contribute, follow the instructions below to get started!
3. Suggestions: If you don't want to code but have some awesome ideas, open up an issue explaining some updates or imporvements you would like to see!
4. Documentation: If you see the need for some additional documentation, feel free to add some!


