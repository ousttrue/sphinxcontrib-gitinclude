% gitinclude documentation master file, created by
% sphinx-quickstart on Mon Oct 18 20:59:07 2021.
% You can adapt this file completely to your liking, but it should at least
% contain the root `toctree` directive.

# gitinclude

```{toctree}
:maxdepth: 2
:caption: Contents
```

## sample

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
``
```

```{gitinclude} HEAD gitinclude/__init__.py
:language: python
:linenos:
```

## Indices and tables
* {ref}`genindex`
* {ref}`modindex`
* {ref}`search`
