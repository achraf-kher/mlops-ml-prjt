# mlops-ml-project (baseline)

## Installation
python -m venv .venv
# activer l'environnement virtuel
pip install -r requirements.txt

## Entraînement
python -m scripts.train

## Évaluation
python -m scripts.evaluate

## Artefacts
- artifacts/model.joblib
- artifacts/metrics.json
- artifacts/confusion_matrix.png
- artifacts/report.json
