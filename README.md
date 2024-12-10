# Bluesky Notebook 🦋

A starter [Jupyter Notebook](https://jupyter.org/) for interacting with the [Bluesky API](https://docs.bsky.app/).

## Quick Start with UV

Follow these steps to set up and run the notebook using [uv](https://docs.astral.sh/uv/). If you don't have `uv` installed, check out [this guide](https://docs.astral.sh/uv/#getting-started).

### 1. Clone the Repository

```bash
git clone https://github.com/filip-melka/bluesky-notebook.git
```

### 2. Create and Activate a Virtual Environment

Navigate to the project directory, create a virtual environment, and activate it:

```bash
cd bluesky-notebook
uv venv --allow-existing .
source bin/activate
```

### 3. Install Required Libraries

Install the `atproto` library and Jupyter Lab:

```bash
uv pip install atproto
uv pip install jupyterlab
```

### 4. Run Jupyter Lab

Start Jupyter Lab to open and interact with the notebook:

```bash
jupyter lab
```

### 5. Configure Your Credentials

Create a `config.json` file in the project root to store your Bluesky credentials:

```json
{
    "email": "your-email@example.com",
    "password": "your-password"
}
```

---

You're all set! Open the notebook in Jupyter Lab, and you're ready to start exploring the Bluesky API.