### SomeRandomStuff.py
- a module made to get info from the some-random-stuff api!
- How to install:
```
pip install -U git+https://github.com/Sengolda/somerandomstuffpy
```
##### Examples
- getting images
```py
from somerandomstuff import Session
print(Session.get_image("cat"))
```
- getting facts
```py
from somerandomstuff import Session
print(Session.get_fact("cat"))
```
- Getting a random token/password
```py
from somerandomstuff import Session
print(Session.get_random_token()))
```
