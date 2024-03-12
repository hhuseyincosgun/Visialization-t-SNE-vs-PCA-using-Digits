# Visualization: t-SNE vs PCA using Digits

**PCA (Principal Component Analysis):**
- Linear technique that finds directions of maximum variance in data.
- Projects data onto these directions, preserving global structure.
- Assumes linear relationships between variables.
- Faster but doesn't capture local structure well.

**t-SNE (t-distributed Stochastic Neighbor Embedding):**
- Nonlinear technique that preserves local structure.
- Constructs probability distributions over pairs of data points.
- Captures nonlinear relationships between variables.
- Slower but excels at preserving local structure.

Choose PCA for faster analysis when preserving global structure is sufficient. Choose t-SNE for capturing intricate local relationships, even if it's slower.
