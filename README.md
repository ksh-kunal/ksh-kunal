<img src="https://i.ytimg.com/vi/0v4FGlGB0Yc/maxresdefault.jpg">

<!-- Zero width character is used to put extra blank lines before and after code -->

<h2>
    
```python
​
from __future__ import annotations

import json
from dataclasses import asdict, dataclass


@dataclass
class Suits:
    Languages I know: tuple[str, ...] = ("Python", "JavaScript", "SQL")
    Databases I have worked on: tuple[str, ...] = ("MySQL", "PostgreSQL","Amazon Redshift")
    Libraries I have tried: tuple[str, ...] = ("Pandas, Numpy", "PyTorch", "OpenCV")
    Ongoing Learning: tuple[str, ...] = ("Django", "Deep Learning", "Cognitive Analytics")
    Things I have strong interests: tuple[str, ...] = ("Data Science", "AI", "FinTech", "Consulting", "Space Tech.")

    def jsonify(self) -> str:
        return json.dumps(asdict(self), indent=4)


suit = Suits()
print(suit.jsonify())
```
</h2>


<h3 align="center">Connect with me:</h3>
<div color: white>
 <p align="center">
<a href="https://twitter.com/kunalsh23552206" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="kunalsh23552206" height="30" width="40" /></a>
<a href="https://linkedin.com/in/kunal-sharma-469962166/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="kunal-sharma-469962166/" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/15271953/kunal-sharma?tab=profile" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/stackoverflow.svg" alt="15271953/kunal-sharma?tab=profile" height="30" width="40" /></a>
<a href="https://kaggle.com/kunalsharma88" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/kaggle.svg" alt="kunalsharma88" height="30" width="40" /></a>
<a href="https://auth.geeksforgeeks.org/user/kushkunal077" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/geeksforgeeks.svg" alt="kushkunal077" height="30" width="40" /></a>
</p>
</div>
