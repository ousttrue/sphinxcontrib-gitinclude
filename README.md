# sphinxcontrib-git_include

`literalinclude` from git repository.
using `git cat-file -p {rev}:{path_to_file}`

## install

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

[Github Actions 使ったらPypiへのリリースがめちゃくちゃ楽になった](https://qiita.com/th4inf/items/d9e575095d35f8f6720e)
