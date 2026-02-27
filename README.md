## Setup

Use Python 3.10-3.13 for this project.

`langchain_core` currently has compatibility issues with Python 3.14+, so the project is pinned to `<3.14`.

### Recreate environment (PowerShell)

```powershell
deactivate
Remove-Item -Recurse -Force .venv
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -U pip
pip install -e .
python client.py
```
