# Urljoin
![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)
https://img.shields.io/pypi/v/CaseInsensitiveDict.svg
https://img.shields.io/pypi/wheel/CaseInsensitiveDict.svg
https://api.travis-ci.org/tivvit/python-case-insensitive-dict.svg?branch=master
https://img.shields.io/github/license/tivvit/python-case-insensitive-dict.svg

When you need to join url paths!

## Install
```
pip install urljoin
```

## Example
```python
import urljoin
urljoin.url_path_join("a", "b")
'a/b'
urljoin.url_path_join("a/", "/b")
'a/b'
urljoin.url_path_join("a", "b", trailing_slash=True)
'a/b/'
```

## Development

Feel free to contribute via pull request or file an issue.

## Copyright and License

&copy; 2017 [tivvit.cz](https://tivvit.cz)

Released under MIT license