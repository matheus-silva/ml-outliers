# Python venv

Useful contents about venvs:

    * Python's venv hands-on video (PT-BR): https://www.youtube.com/watch?v=m1TYpvIYm74
    * Python documentation (EN): https://docs.python.org/3.6/library/venv.html

1. Install Python's venv:

    sudo apt-get install python3-venv

2. Create a venv. Usually, the name used for a venv is `venv`:

    python3 -m venv venv

3. Activate the new venv:

    source ./venv/bin/activate

4. Install a library inside the venv:

    pip install <library>

5. Install all the libraries from a requirements file:

    pip install -r requirements.txt

6. Create a requirements file for the libraries inside the venv:

    pip freeze > requirements.txt

7. Deactivate the new venv:

    deactivate

