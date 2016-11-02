# Code2040 API Challenge 
# Step 1 - Registration 

import json 
import requests

def create_token():

github= "https://github.com/msnewman21/Code2040.git"
info = {'email': adamma.newman@bison.howard.edu, 'github': githubUrl}

final = request.post(github, info)
token = json.loads(final.text)["result"]
