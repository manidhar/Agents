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

## Run The ADK Agent

After activating the virtual environment, start the agent with:

```bash
adk run firstagent
```

The agent uses the Ollama model from the `OLLAMA_MODEL` environment variable.
If `OLLAMA_MODEL` is not set, it falls back to `ollama_chat/gemma4`.

To check whether the model exists on your local machine, run:

```bash
ollama list
```

Compare the model name after `ollama_chat/` with the names in the list.
For example, `ollama_chat/gemma4` means the local Ollama model should be `gemma4`.

If your model does not appear in the list, pull it first. For example:

```bash
ollama pull gemma4
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
