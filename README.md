## Graph Reconstruction Module and Graph Inference Module
1. The autoencoder used in our graph reconstruction module is similar to the one used in https://arxiv.org/abs/1609.02907.
2. Both modules are implemeneted by Graph_Reconstruction_Infer.ipynb

## Graph Anomaly Detection Module
1. The implementation of baseline models with/without RE-GAD is achieved on the basis of the codes of https://github.com/squareRoot3/GADBench
2. Benchmark all methods on all 10 datasets in the semi-supervised setting (10 trials).

```
python benchmark.py --trial 10  --semi_supervised 1 