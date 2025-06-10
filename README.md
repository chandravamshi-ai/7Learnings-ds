# 7Learnings Data Science Coding Challenge

## 🔧 Environment Setup

To set up the project environment:

```bash
# Create and activate virtual environment
python3 -m venv 7learning
source 7learning/bin/activate

# Install required dependencies
pip install -r requirements.txt
````

**Google Cloud Setup** (for BigQuery access):

```bash
# Install Google Cloud SDK (macOS)
brew install --cask google-cloud-sdk

# Initialize and authenticate
gcloud init
gcloud auth application-default login
```

---

## 📂 Project Structure

* `7learnings.ipynb`: Final Jupyter notebook with all tasks, code, and explanations.
* `gsod_data_cleaned.csv`: Dataset which I collected form Bigquery
* `requirements.txt`: Dependencies used.
* `coding_challenge.csv`: Provided dataset (used for fallback).

