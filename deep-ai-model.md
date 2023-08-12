# deep ai
a python script for use free of bing chat bot with use request sampler.

### Getting start
entry point of app here:
```python
# ./deepai.py

...
_create_completion([{
    "role": "stirng",
    "content":"string"
}])
```

for run app you just need start script.py file in python
`python ./deepai.py`

## entites:
message model is a json object and use for send message prompt to chat bot 
for proccess and return data. sample of json object:
```json
{
  "role": "assistant|user|system",
  "content": "string message prompt"
}
```
