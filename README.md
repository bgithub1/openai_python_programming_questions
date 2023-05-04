### Ask the GPT API a set of Python Programming Questions 
##### (some from https://www.geeksforgeeks.org/python-programming-examples/)

#### Installation:
Using python 3.9+
1. Create a new Virtualenvs environment using venv (or something similar)
2. From a bash terminal run:
  * source your_virtual_env_folder_path/bin/activate
  * pip install -r your_project_folder/requirements.txt

#### To Run:
1. Make sure you put a valid OpenAI API key in the file ```temp_folder/api_key.txt```
2. Run all cells in this notebook

#### Output:
In the folder ```temp_folder```, there will be 2 files:
1. ```programing_question_responses.json```: This file contains the full json output from GPT for all 129 programming questions
2. ```code_snippits.txt```: This file has just the question text and the response text