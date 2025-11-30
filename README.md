## Learning-Journey-AI-Agent-Masterclass
This repo is a type of get-your-hands-dirty session of learning on building AI agent from scratch via AI agent masterclass by Cole Madin <br>
The github original repo is here: https://github.com/coleam00/ai-agents-masterclass <br>
The youtube video links is here: https://www.youtube.com/@ColeMedin/playlists

## Instructions to Follow Along

The below instructions assume you already have Git, Python, and Pip installed. If you do not, you can install [Python + Pip from here](https://www.python.org/downloads/) and [Git from here](https://git-scm.com/downloads).

To follow along with any of my videos, first clone this GitHub repository, open up a terminal, and change your directory to the folder for the current video you are watching (example: 1st video is `/1-first-agent/`).

The below instructions work on any OS - Windows, Linux, or Mac!

You will need to use the environment variables defined in the .env.example file in the folder (example for the first video: `1-first-agent/.env.example`) to set up your API keys and other configuration. Turn the .env.example file into a `.env` file, and supply the necessary environment variables.

After setting up the .env file, run the below commands to create a Python virtual environment and install the necessary Python packages to run the code from the masterclass. Creating a virtual environment is optional but recommended! Creating a virtual environment for the entire masterclass is a one time thing. Make sure to run the pip install for each video though!

```
python -m venv ai-agents-masterclass

# On Windows:
.\ai-agents-masterclass\Scripts\activate

# On MacOS/Linux:
source ai-agents-masterclass/bin/activate

cd 1-first-agent (or whichever folder)
pip install -r requirements.txt
```

Then, you can execute the code in the folder with:

```
python [script name].py
```
