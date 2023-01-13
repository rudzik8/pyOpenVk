# pyOpenVk
Проста у використанні реалізація OpenVk Api

## Installing

```
pip install openvk
```


## Quick Example
```python
from openvk import openvkapi
from openvk import messages


client = openvkapi.auth(login='youre@gmail.com', password='password')
user_id = 1010
messages.send(client, user_id, 'Hello world!')
```

## Links
[LeenzeryDev](https://github.com/leenzerydev)             
[.NET version](https://github.com/LyStudios/OpenVkNetApi)  
