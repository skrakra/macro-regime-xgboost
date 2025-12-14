## Requirements

The project depends only on a few core Python packages:

pandas>=2.3.0
numpy>=1.26.0
scikit-learn>=1.5.0
optuna>=4.0.0
ipykernel>=6.29.0


These are listed in `requirements.txt`.

---

## Setup

You can run the project directly in your preferred notebook environment if these packages are already installed, or create a fresh environment as follows:

```bash
# (Optional) Create and activate a new virtual environment
python -m venv env
source env/bin/activate        # On macOS/Linux
# .\env\Scripts\Activate       # On Windows

# Install dependencies
pip install -r requirements.txt