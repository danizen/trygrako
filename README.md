# Using Grako

This is a very simple demonstration of the use of the Grako parser
generator in Python.   No attempt is made to productize, I just
wanted to minimally understand the ebnf input to grako.

## Generating expr.py

```
pip install -r requirements.txt
grako expr.ebnf > expr.py
```

## Running expr.py

```
python expr.py data/valid
python expr.py data/invalid
```


