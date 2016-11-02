# Code2040 API Challenge 
# Step 1 - Registration 

import json 
import requests

def create_token():

github= "https://github.com/msnewman21/Code2040.git"
url = "http://challenge.code2040.org/api/register"
info = {'email': adamma.newman@bison.howard.edu, 'github': github}

final = requests.post(url, info)
token = json.loads(final.text)["result"]
