
https://packaging.python.org/tutorials/packaging-projects/

Installs needed
```
python -m pip install --upgrade build
pip install twine
```
1) In the directory . open a command prompt (eg in vscode)
2) Increment the version in setup.cfg in the project IMPORTANT
3) cmd: python -m build
4) cmd: python -m twine upload --repository pypi dist/*
The credentials are stored in a settings file
5) Check success https://pypi.org/manage/projects/