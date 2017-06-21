# python-voluum
Python client for Voluum API

More about Voluum API: https://developers.voluum.com/


# Installation:

`pip install python-voluum`


# Usage:

``` python
from voluum import Client

client = Client()
client.authenticate(email='voluumdemo@voluum.com', password="1qaz!QAZ")
client.get_campaign_list()
```
