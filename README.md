# sphinxcontrib-git_include

<https://github.com/ousttrue/sphinxcontrib-git_include>

`literalinclude` from git repository.

using `git cat-file -p {rev}:{path_to_file}`

## install

```
> pip install gitinclude
```

## Sample 

<https://ousttrue.github.io/sphinxcontrib-gitinclude/>

### Sphinx: conf.py

```py
extensions = [
    "gitinclude",
]
```

### Sphinx: usage

`myst`

```
``{gitinclude} HEAD^ gitinclude/__init__.py
:language: python
:linenos:
``
```
