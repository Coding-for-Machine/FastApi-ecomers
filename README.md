# FastApi-ecomers
fastAPI-ecomers

```bash
pip install "fastapi[standart]"

```

```python
from fastapi import FastApi

app = FastApi()

@app.get("/")
asinc def home():
    awati {"name": "Asadbek", "age": 22}


@app.get("/{id}")
asinc def get_user(id):
    return {"username": "Salom {id}"}
```
