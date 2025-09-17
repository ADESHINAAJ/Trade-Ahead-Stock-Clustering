# Trade-Ahead-Stock-Clustering
Unsupervised clustering of stocks by fundamentals/performance. Scaled features, K-means and hierarchical clustering; elbow/silhouette/dendrogram selection; cluster profiling with investment insights. Python, scikit-learn, visualisation.

**Commit message:** `Initial commit: ReneWind failure classification notebook and README`

---

## 7) Trade Ahead

```markdown
# Trade & Ahead: Stock Clustering

Cluster stocks by performance/financial attributes and profile each cluster for investment insight.

## Overview
- **Goal:** Group similar stocks and interpret cluster characteristics.
- **Techniques:** EDA, K-means, Hierarchical clustering, elbow/silhouette, dendrograms, cluster profiling.

## Data
Coursework stocks data (not included). Features may include P/E, cash ratio, net income, returns/volatility.

## How to Run
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
