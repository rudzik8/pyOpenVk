# pyOpenVk

### Installing

```
pip install pyOpenVk
```


### Quick Example
```python
from pyOpenVk import api
from pyOpenVk import messages


client = api.auth(login='youre@gmail.com', password='password')
user_id = 1010
messages.send(client, user_id, 'Слава Україні!')
```

### Links
[LeenzeryDev](https://github.com/leenzerydev)             
[.NET version](https://github.com/LyStudios/OpenVkNetApi)  
