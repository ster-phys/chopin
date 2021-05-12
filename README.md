# chopin
This repository is intended to make it easier to use the Chopin's compositions.
It does not follow any coding conventions :)

## Requires
```sh
$ pip install requests youtube_dl
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

>>> print(type(foo.links[0]))
<class 'chopin.chopin.Link'>

>>> print(dir(foo.links[0]))
['ID', 'artists', 'delete', 'download', 'url']
```
