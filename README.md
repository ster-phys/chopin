# chopin
This repository is intended to make it easier to use the Chopin's compositions.
It does not follow any coding conventions :)

## How to Install
```sh
$ git clone git@github.com:ster-phys/chopin.git
$ cd ./chopin
$ pip install -U .
```

## How to Use
- Example
```python
import chopin

ch = chopin.chopin()

print(ch.compositionList)
print(ch.genreList)
ch.get() # -> Composition
ch.gets() # -> Composition
ch.genre() # -> [Composition]
```

- Composition & Link
```python
>>> print(type(foo))
<class 'chopin.chopin.Composition'>

>>> print(dir(foo))
['No', 'Opus', 'links', 'title', 'wikiLink']

>>> print(type(foo.links))
<class 'list'>

>>> print(dir(foo.links[0]))
['ID', 'artists', 'delete', 'download', 'url']
```
