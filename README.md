# nidongde
🔞nidongde is a Chinese phrase for "you know". Please control yourself!

Make sure you are older than 18!

## Requirement
requests
bs4
fake-useragent


## Scripts

### load.py (deprecated)
load vedios

### search.py (deprecated)
search vedios with keywords (and styles)

### load_novels.py
load novels.

### load_movies.py (recommended)
Load movies with OOP, integrate load.py and search.py.
```python
Movie.load  == load in load.py
Movie.search == search in search.py

# Examples
# load 29960, 29961, 29963, 29964-29971, 34538-34543
Moive.load([29960, [29961, 29963], (29964, 29971), (34538, 34543)])

# search movies with '人妻'
for m in Movie.search('人妻')：
    print(m)
```

## clt

```bash
script.py load -i [index] (-v)
script.py search -k keyword -s style -m (mask method)
```
mask method: `mask`, `random` or any digit for Caesar

## misc
I get first `✭star` in my github-life.

## Similar project
* [Porndl](https://github.com/Ybow/porndl)
* [FBIWarning](https://github.com/nusr/FBIWarning)
* [Pornsearch](https://github.com/LucasLeandro1204/Pornsearch)
