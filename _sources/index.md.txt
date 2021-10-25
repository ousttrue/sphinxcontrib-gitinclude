% gitinclude documentation master file, created by
% sphinx-quickstart on Mon Oct 18 20:59:07 2021.
% You can adapt this file completely to your liking, but it should at least
% contain the root `toctree` directive.

# gitinclude

## sample

### Sphinx: conf.py

```py
extensions = [
    "gitinclude",
]
```

### Sample

```
``{gitinclude} HEAD README.md
:language: markdown
:linenos:
``
```

```{gitinclude} HEAD README.md
:language: markdown
:linenos:
```

```
``{gitinclude} HEAD gitinclude/__init__.py
:language: python
:linenos:
:lines: 109-117
``
```

```{gitinclude} HEAD gitinclude/__init__.py
:language: python
:linenos:
:lines: 109-117
```

## error
```{gitinclude} HEAD xxx.py
:language: python
:linenos:
```

## Indices and tables
* {ref}`genindex`
* {ref}`modindex`
* {ref}`search`
