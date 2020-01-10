This repository is an example showcasing [michaeljones/breathe#470](https://github.com/michaeljones/breathe/issues/470).

To reproduce, create a virtual environment with `sphinx` and `breathe` installed, then execute:


```shell
cd docs
doxygen
sphinx-build -b html . _build
```

This should produce a warning like this:

```
../docs/index.rst:6: WARNING: Duplicate declaration, END
```

