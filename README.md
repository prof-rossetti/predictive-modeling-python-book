# Predictive Modeling in Python

Source repository for the interactive online book **"Predictive Modeling in Python"** by Michael J. Rossetti.

- **Online Edition**: [https://prof-rossetti.github.io/predictive-modeling-python-book/](https://prof-rossetti.github.io/predictive-modeling-python-book/)
- **Quarto Source**: `docs/`

---

## 💻 Environment Setup

Create and activate a dedicated Conda environment using **Python 3.13** (matching Google Colab's current runtime), then install dependencies:

```bash
conda create -n predictive-modeling-book python=3.13 -y
conda activate predictive-modeling-book
pip install -r docs/requirements.txt
```

---

## 🛠️ Development & Standards

This book adheres to shared publishing, environment, and verification standards maintained in [prof-rossetti/quarto-book-skills](https://github.com/prof-rossetti/quarto-book-skills):

- **Dedicated Conda Environment**: `predictive-modeling-book` with Python 3.13 and an isolated Jupyter kernel.
- **Google Colab Parity**: Dependencies in `docs/requirements.txt` and tutorial code cells match Colab's default runtime versions.
- **CI/CD Publishing**: Automated GitHub Pages builds via `.github/workflows/deploy.yml`.

### Agentic Development with Antigravity
If developing with Google Antigravity, connect the skills suite by adding the following to your `~/.gemini/config/skills.json`:

```json
{
  "entries": [
    { "path": "~/projects/prof-rossetti/quarto-book-skills/skills" }
  ]
}
```
