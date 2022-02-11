# Flask Quickstart:
https://flask.palletsprojects.com/en/2.0.x/quickstart/

# Activate virtual environment (in BASH):
source C:/Users/Bruce/.virtualenvs/lab03_Blog-hZbHCgGA/Scripts/activate

$ pip list
Package    Version
---------- -------
pip        21.3.1
setuptools 60.5.0
wheel      0.37.1

# Install Flask
pipenv install flask

$ pip list
Package      Version
------------ -------
click        8.0.3
colorama     0.4.4
Flask        2.0.2
itsdangerous 2.0.1
Jinja2       3.0.3
MarkupSafe   2.0.1
pip          21.3.1
setuptools   60.5.0
Werkzeug     2.0.2
wheel        0.37.1

$ cat Pipfile
[[source]]
url = "https://pypi.org/simple"
verify_ssl = true
name = "pypi"

[packages]
flask = "*"

[dev-packages]

[requires]
python_version = "3.10"


