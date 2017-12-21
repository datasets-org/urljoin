# Urljoin
![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)

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

## Disclaimer
Works only in python3 (because of `kwargs` after `*args` https://stackoverflow.com/questions/15301999/python-2-x-default-arguments-with-args-and-kwargs)

## Development

Feel free to contribute via pull request or file an issue.

##Copyright and License

&copy; 2017 [tivvit.cz](https://tivvit.cz)

Released under MIT license