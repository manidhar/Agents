# Agents

## Python Environment Setup

Create a virtual environment in the project root:

```bash
python3 -m venv aiagents
```

Activate it on macOS:

```bash
source aiagents/bin/activate
```

Activate it on Windows PowerShell:

```powershell
aiagents\Scripts\Activate.ps1
```

Activate it on Windows Command Prompt:

```cmd
aiagents\Scripts\activate.bat
```

Install the project dependencies after activation:

```bash
pip install -r requirements.txt
```

To check whether a package is installed, run:

```bash
pip show package_name
```

If the package is installed, `pip show` displays its details. If it is not installed, it returns no result.

To leave the virtual environment, run:

```bash
deactivate
```
