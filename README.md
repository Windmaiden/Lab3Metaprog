1. Run unit tests:
```
python -m unittest discover -s test/py2sql/
```

2. Docs were built using this guide https://stackoverflow.com/questions/59903051/sphinxs-autodocs-automodule-having-apparently-no-effect
Sphinx automatically reads the docs
It needs rst files as well as conf.py to be updated and maintained.

You will be able to interactively view the changes being done to the database.

3. Build the project:
```
python setup.py sdist
twine upload dist/*
```
