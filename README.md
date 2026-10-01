## Setup

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the project dependencies:

```bash
python -m pip install -r requirements.txt
```

To confirm the virtual environment is active:

```bash
which python
```

The returned path should point to the project's `.venv` directory.

When finished working on the project, deactivate the environment with:

```bash
deactivate
```

### Troubleshooting Jupyter kernels

If the notebook appears to be using the wrong Python environment, run:

```python
import sys
print(sys.executable)
```

The path should point to the project's .venv directory.
For example /Users/caroline/Desktop/workspace/data-handling-and-infrastructure/data-handling-ai-project/.venv/bin/python
