# data-wrangling-script-collection
collection script for data wrangling.


# Table Of Content
- [HTTP GET/POST](#http-get-or-post)
  - [GET Request](#get-request)

# HTTP GET or POST
## GET Request
```
import requests
import json

url = 'https://xxxx'
access_token = 'xxxxx.xxx'
header = {'Authorization': "Bearer " + access_token,'Accept':'application/json'}
resp = requests.get(url = url, headers = header) 
response = resp.json()
print(response)
```
