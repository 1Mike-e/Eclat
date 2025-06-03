# Eclat Association Rule Mining (Simulated with `apyori`)

This project performs **Eclat-style association rule mining** using the `apyori` Python package. Although `apyori` is built for the Apriori algorithm, this implementation mimics the **Eclat approach** by focusing on **frequent itemsets with high support**, and omits confidence and lift in the final output.

---

## 📁 Dataset

- **Filename**: `Market_Basket_Optimisation.csv`
- **Format**: CSV with no header
- **Rows**: 7,501 transactions
- **Columns**: Up to 20 items per transaction

---

## 📦 Dependencies

Install required packages with:

```bash
pip install apyori numpy pandas matplotlib
