# GPT-2 Fine-Tuned Model for Turkish Legal Text Classification

This repository contains evaluation results of a GPT-2 model fine-tuned for
**Turkish legal text classification** tasks.

## 📊 Test Metrics

| Metric        | Value  |
|--------------|--------|
| Eval Loss    | 1.5059 |
| Accuracy     | 0.6000 |
| Precision    | 0.6167 |
| Recall       | 0.6000 |
| F1-Score     | 0.6022 |

## 🧪 Token Statistics

- Total Train Tokens: **30,595**
- Total Test Tokens: **7,680**
- Grand Total Tokens: **38,275**

## 📌 Labels Used

- Ceza
- Borç
- Mülkiyet
- Mahkeme uyuşmazlık

## 📂 Files

- `results/test_metrics.json` → Evaluation metrics
- `results/prediction_samples.json` → Sample predictions
- `results/token_statistics.json` → Token usage statistics
- `data/data.json` → Dataset used for fine-tuning

## 🧠 Model

- Base Model: **GPT-2**
- Language: **Turkish**
- Domain: **Legal / Court Decisions**

## ⚠️ Disclaimer

This model is for **research purposes only** and should not be used as a legal advisory system.
