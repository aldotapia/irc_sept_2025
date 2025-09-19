# IRC Sept 2025

## Installation

First install uv for package management:

On macos/linux:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

On windows:
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Then install the packages:
```bash
uv venv
source .venv/bin/activate
uv sync
cd superflexPy
uv pip install -e .
```
