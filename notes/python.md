# Python

* Publish python package at PyPi

```bash
pip install twine, setuptools
python setup.py bdist_wheel
twine upload ./dist/ADBox-0.1.1-py3-none-any.whl
```
