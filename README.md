## Setup
Follow [this guide](https://www.spletzer.com/2024/04/a-no-nonense-guide-to-setting-up-python-environments/)

* **Install:** `pyenv install <PYTHON_VERSION>`
* **Activate:** `pyenv activate <PROJECT_NAME>` OR `pyenv virtualenv <PYTHON_VERSION> <PROJECT_NAME>`
* **Set:** `pyenv local <PROJECT_NAME>`

## Jupyter Notebook 
**Register Jupyter Notebook with pyenv:** 
```bash
python3 -m ipykernel install --user --name=<PROJECT_NAME> --display-name "My Python Notebook"
```
**Run Notebook:** 

Assuming we've done `pip install jupyter` (`pip install ipykernel` might also be required):

Now we can do:
```bash
jupyter lab
```
OR
```bash
jupyter notebook
```
