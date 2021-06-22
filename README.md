# Pandas

Pandas data processing Jupyter notebook for blog post. The datasets are taken from the [Kitsune Network Attack Dataset](https://www.kaggle.com/ymirsky/network-attack-dataset-kitsune). You will need to download the files: `OS_Scan.pcap, SYN_Dos.pcap` and export these to csv. The Mirai csv is already included, the other two files were too large to be in the repo.

## Install dependencies

All the Python dependencies can be installed using poetry. Follow the steps below:

1. [Install Poetry](https://python-poetry.org/docs/#installation).

2. Install dependencies using: `poetry install`.

3. Switch to the poetry virtual environment: `poetry shell`.

4. Run: `which python` and copy the full path of the Python interpreter to `.vscode/settings.json` substituting the variable: `"python.pythonPath": <full_path_to_python_env_var>`

5. Change the Jupyter notebook kernel to the poetry venv Python path.
