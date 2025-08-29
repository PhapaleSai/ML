# Machine_learning
Machine_learning_sai

# IMP CODE
import requests

url = "https://raw.githubusercontent.com/PhapaleSai/Machine_learning/main/1st_code"
response = requests.get(url)

if response.status_code == 200:
    print(response.text)
else:
    print(f"Failed to fetch file — status code: {response.status_code}")
