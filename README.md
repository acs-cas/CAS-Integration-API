
<img width="300" height="173" alt="CAS_PREF_3C_RGB_POS (4)" src="https://github.com/user-attachments/assets/955fa8ff-d341-429b-bfaa-a1cbed475a4f" />

# CAS API

The CAS API supports workflow integration, chemical research, machine learning, and cheminformatics.  Learn more about workflow integration solutions from __[CAS Custom Services℠](https://www.cas.org/solutions/cas-custom-services/workflow-integration).__

## CAS API Demo for server-to-server integration

The Juyter Notebook files in this demo are meant to demonstrate how to invoke the CAS API in a server-to-server use case.  For this case, the API implements the 'Client Credentials Flow' as described here: [Client Credentials Flow](https://oauth.net/2/grant-types/client-credentials/)

## Installation

You will need an installation of Python and pip pre-installed.  This project uses Python 3.13.

First, create a virtual environment in the same directory within which the notebook files (.ipynb) reside:
```bash or Windows Powershell
python -m venv .venv
```

Activate the virtual environment.  On a linux-based system, do this:
```bash
source .venv/bin/activate
```
On a Windows system, do this:
```Windows Powershell
.\.venv\Scripts\activate.ps1
```

Finally, install the dependencies that are defined in the requirements file:
```bash or Windows Powershell
pip install -r requirements.txt
```

## Usage

You will need a tool or an IDE that can execute Jupyter Notebooks.  VS Code and Pycharm are examples.  You will also need to ensure that the Python environment for the tool you choose has been set to the virtual environment that you created in the previous steps.  For example, in VS Code, enter 'CNTRL-SHIFT P' and select 'Python: Interpreter' and then select your virtual environment.  Once that is done, you should be able to execute the sections of the notebook files. 

