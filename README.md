# fruit-harvest-GNN-prediction
GraphSAGE and GCN comparison for blueberry fruit loss and output prediction
# 🧠 Fruit Harvesting Prediction using GNN (GraphSAGE vs GCN)

This project applies Graph Neural Networks (GNNs) to predict:
- 🍇 Fruit Loss (%)
- 📦 Total Fruit Output (grams)

using node features from harvesting conditions and adjacency structure.

---

## 📁 Files
- `Graphsage_model.ipynb`: Main model training notebook
- `Berry_harvest_Norm_New.csv`: Harvest dataset (normalized)
- `Final_Combined_Adjacency_Matrix__Symmetric_6___RowID_.csv`: Graph structure (symmetric)
- Result images in `/results/` folder

---

## 🧪 Models Compared
- GCN (Graph Convolutional Network)
- GraphSAGE (Sample and Aggregate)

---

## 📊 Results Summary

| Metric         | GCN        | GraphSAGE   |
|----------------|------------|-------------|
| R² Fruit Loss  | ~0.16      | ~0.83       |
| R² Output      | ~0.29      | ~0.83       |
| RMSE Fruit Loss| ~0.27      | ~0.12       |
| RMSE Output    | ~0.15      | ~0.07       |

📉 GraphSAGE clearly outperformed GCN in both metrics.

