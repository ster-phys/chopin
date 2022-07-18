# chopin

This repository is intended to make it easier to use the Chopin's compositions.
It does not follow any coding conventions :)

[![](https://img.shields.io/pypi/pyversions/chopin)](https://www.python.org/)
[![](https://img.shields.io/pypi/v/chopin)](https://pypi.org/project/chopin/)
[![](https://img.shields.io/github/license/ster-phys/chopin)](https://opensource.org/licenses/MIT)

## How to Install

```sh
$ pip install chopin
```

### Requires

- [youtube_dl](https://github.com/ytdl-org/youtube-dl)

## How to Use

### Example

```python
>>> from chopin import Chopin
>>> chopin = Chopin()
>>> content = chopin.download()
>>> print(content.path)
'/tmp/XXXXXXXXXXX.mp3'
>>> content.remove()
```
