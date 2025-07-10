# ProvingDataDrift

This repository contains a dataset `MSL_train.npy` and example notebooks for visualizing it.

## Visualizations

- `visualize.ipynb` demonstrates PCA, t-SNE, and UMAP on the dataset.
- `visualize_segments.ipynb` loads the dataset, splits it into five chronological sections, and displays each section with a different color using PCA.

To open the segmentation visualization:

```bash
jupyter notebook visualize_segments.ipynb
```

Make sure `numpy`, `scikit-learn`, and `matplotlib` are installed in your environment.
