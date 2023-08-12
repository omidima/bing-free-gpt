# bing-free-gpt
a python script for use free of bing chat bot with use request sampler.

### Update:
> now bing added recaptcha verification. if can pass recaptcha, can use this script else dont work this provider.

## Getting start:
entry point of app here:
```python
# ./bing.py

...
asyncio.run(_create_completion([""]))
```

for run app you just need start script.py file in python
`python ./bing.py`

## entities:
message model is a json object and use for send message prompt to chat bot 
for proccess and return data. sample of json object:
```json
{
  "role": "assistant|user",
  "content": "string message prompt"
}
```
