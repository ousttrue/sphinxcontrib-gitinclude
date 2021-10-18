# sphinxcontrib-git_include

`literalinclude` from git repository.
using `git cat-file -p {rev}:{path_to_file}`

## pypi

```
pip install gitinclude
```

## Sample

`conf.py`

```py
extensions = [
    "gitinclude",
]
```

```
``{gitinclude} HEAD^ gitinclude/__init__.py
:language: python
:linenos:
``
```

## upload

```
py -m build
twine upload dist/*
```
