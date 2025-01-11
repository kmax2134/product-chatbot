Product Chat Bot

If you don't have anaconda download from here https://www.anaconda.com/download/success 

Create a Conda environment:
conda create -p <env_name> python=3.10 -y

Activate your conda environment
conda activate <env_path>

If activating on bash terminal use this command:
source activate ./<env_name> 

ELSE
conda activate <env_path>

Create a requirement.txt file and install it
pip install -r requirements.txt


Create a .env file for keeping your environment variable.

GROQ_API_KEY = ""

ASTRA_DB_API_ENDPOINT = ""

ASTRA_DB_APPLICATION_TOKEN = ""

ASTRA_DB_KEYSPACE = "default_keyspace"

HF_TOKEN = ""


