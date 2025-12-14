# GNN Pruning Analysis (Citeseer)
This project contains a comparative analysis of three graph pruning techniques applied to a Graph Neural Network (GNN) model using the Citeseer dataset.

The goal is to analyze the trade-off between reducing the model's size (sparsity/speedup) and maintaining its predictive performance (accuracy).

## Pruning Methods Analyzed

Gradient Pruning: Method based on the model's loss gradient.

Saliency Pruning: Method based on importance/attention scores.

Random Pruning: Baseline method where edges are removed without criteria.

## How to Run
Dependencies: Ensure you have Python, PyTorch, and the torch-geometric library installed.

Run the Notebook: Execute all cells sequentially in the file.

The notebook performs the following steps:

Loads the dataset.

Defines and initializes a GAT/GCN model.

Simulates the expected performance results (accuracy and time) for comparison.

Calculates real structural metrics (Homophily and Degree Distribution) for the pruned graphs.

## Summary
The analysis provides a visual and quantitative comparison of how different pruning strategies impact the overall graph structure and the model's efficiency.
