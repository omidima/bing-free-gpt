# bing-free-gpt
a python script for use free of bing chat bot with use request sampler.

## requirement:
- python: 3.9
- os: Linux or Unix based system
- connection: high speed network connection > if you run this script in iran need to change IP address to US.

## Tested on:
- os: mac version 13
- python: 3.11

## Getting start
before use bot script you need install project packages. follow this step to install project packages:
1. `python3 -m venv .venv` or `python -m venv .venv`
2. `source .venv/bin/activate`
3. `pip install -r re.txt`

**run app**
entry point of app here:
```python
# ./script.py

...
asyncio.run(_create_completion([""]))
```

for run app you just need start script.py file in python
`python ./script.py`

# Models:
message model is a json object and use for send message prompt to chat bot 
for proccess and return data. sample of json object:
```json
{
  "role": "assistant|user",
  "content": "string message prompt"
}
```
