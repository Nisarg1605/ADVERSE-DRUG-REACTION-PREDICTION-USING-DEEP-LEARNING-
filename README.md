# 💊 Adverse Drug Reaction (ADR) Prediction Using Deep Learning

This project focuses on predicting Adverse Drug Reactions using advanced Deep Learning and Cheminformatics techniques. By leveraging molecular structure data, graph-based models, and sequence analysis, the project aims to accurately forecast potential side effects of pharmaceutical compounds.

---

## 🧠 Objective

* Predict ADRs based on molecular features
* Utilize advanced deep learning architectures including CNN, LSTM, and GCN
* Combine multiple representations (SMILES strings, molecular graphs, fingerprints)
* Enable safer drug development through predictive analytics

---

## 🛠️ Tech Stack

* Python (PyTorch, Keras, RDKit, DGL/PyTorch Geometric)
* Deep Learning: CNN, LSTM, GCN, ChemBERTa
* Fingerprint analysis: Morgan, MACCS
* Data: DrugBank, SIDER

---

## 🧪 Models Used

| Model     | Input Type        | Notes                                  |
| --------- | ----------------- | -------------------------------------- |
| CNN       | SMILES            | 1D Convolutions over tokenized SMILES  |
| LSTM      | SMILES            | Sequence modeling of molecular strings |
| GCN       | Molecular Graphs  | RDKit + PyTorch Geometric              |
| Hybrid    | CNN + GCN + LSTM  | Soft voting / stacking                 |
| ChemBERTa | SMILES Embeddings | Transformer-based molecular encoder    |

---

## 👤 Author

**Nisarg Patel**
🔗 [GitHub](https://github.com/Nisarg1605) | 📧 [LinkedIn](https://www.linkedin.com/in/nisarg-patel-a5784124b/)

