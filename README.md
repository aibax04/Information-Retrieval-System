# Information-Retrieval-System
How to run?
STEPS:
Clone the repository

Project repo: https://github.com/
STEP 01- Create a conda environment after opening the repository
conda create -n llmapp python=3.8 -y
conda activate llmapp
STEP 02- install the requirements
pip install -r requirements.txt
Create a .env file in the root directory and add your GOOGLE_API_KEY as follows:
GOOGLE_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
# Finally run the following command
streamlit run app.py
Now,

open up : http://localhost:8501
Techstack Used:
Python
LangChain
Streamlit
PaLM2
FAISS
