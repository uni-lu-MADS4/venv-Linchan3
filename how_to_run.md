# How to Run Q01.py with pip and venv

## Step 1: Create a venv and activate it
Run the following commands in your terminal to create a virtual environment:

### For Mac/Linux:
```bash
python3 -m venv ADDRESS_TO_VENV_FOLDER
```

### For Windows:
```bash
py -3.9 -m venv ADDRESS_TO_VENV_FOLDER
```

### Notes:
- Replace `ADDRESS_TO_VENV_FOLDER` with the path to your desired folder.
- The folder name of the venv should **not contain spaces** and should be empty.
- If you are reusing the folder, you may use the `--clear` or `--upgrade` options.
- Use `deactivate` to exit the virtual environment.

### Example (.venv is a common name):
```bash
python3 -m venv .venv
```

Activate the venv:

#### For Linux/MacOS (bash/zsh):
```bash
source ADDRESS_TO_VENV_FOLDER/bin/activate
```

#### For Windows (Command Prompt):
```bash
ADDRESS_TO_VENV_FOLDER\Scripts\activate.bat
```

#### For Windows (PowerShell):
```bash
ADDRESS_TO_VENV_FOLDER\Scripts\Activate.ps1
```
#### Example (with the name .venv):
source .venv/bin/activate
---

## Step 2: Install the required packages and run Q01.py
With the virtual environment activated, install the dependencies and run the script:

```bash
pip install -r requirements.txt
python Q01.py
```
