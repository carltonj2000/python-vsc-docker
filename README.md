# Python And VSCode Example

Run the app via:

```bash
pip install -r requirements.txt
export set FLASK_APP=webapp
cd hello_app
python3 -m flask run
```

## Setup

```bash
sudo apt-get install python3-venv    # If needed
python3 -m venv env
```

After the above:

- verify vscode lower left shows that python in the venv is being used
- restart the terminal and verify you are in the venv
  - you are in a venv if the start of the prompt shows "(env)"
  - basically it does "sources ./env/bin/activate"

```bash
sources ./env/bin/activate # needed if env is not auto sourced
python3 -m flask run
pip freeze > requirements.txt
pip install -r requirements.txt
```

## History

The code in this repository is based on the following articles.

- [Getting Started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial)
- [Flask Tutorial in Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-flask)
- [Python in a container](https://code.visualstudio.com/docs/containers/quickstart-python)
