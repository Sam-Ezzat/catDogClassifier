# 🐱🐶 Cats vs Dogs Classifier

A production-grade ML project for binary image classification.
- Framework: PyTorch
- Config system: Hydra
- Serving: FastAPI
- CI: GitHub Actions
- Tracking: MLflow

## Quickstart
1. Clone repo
2. Install dependencies: `pip install -e .`
3. Train: `python scripts/train.py`
4. Serve API: `uvicorn mlproj.serve.api:app --reload`