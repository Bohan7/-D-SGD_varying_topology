# Iterative Improvement on Different Topologies under the Effect of Heterogeneous Data with Decentralized SGD 

| Student's name | Institution |
| -------------- | ------ |
| Chun Hei Michael Chan | École polytechnique fédérale de Lausanne (EPFL) |
| Bohan Wang | École polytechnique fédérale de Lausanne (EPFL) |
| Qi Yi| École polytechnique fédérale de Lausanne (EPFL) |

This project provide an insight into the effect of Heterogeneous Data on the topology of Decentralized SGD. The results and discussion of the project are demonstrated in the [report](https://github.com/Bohan7/D-SGD_varying_topology/blob/main/Iterative_Improvement_on_Different_Topologies_under_the_Effect_of_Heterogeneous_Data_with_Decentralized_SGD.pdf).

## Description
Our code is largely notebook based to show plots and results relayed in the report. 
Main points are as follows:
    
    - iid distribution for D-SGD for various topology (part 1)
    - non-iid distribution for D-SGD for various topology (part 2)
    - non-iid distribution for D-SGD for iteratively modified starting topologies (part 3)
    
```
differrentTopology.ipynb     : notebooks computing plots for part 1 and 2
Algo1_findTopology.ipynb     : notebooks computing plots for part 3
Algo1_selectedTopology.ipynb : notebooks computing plots for part 3
experimentsPlot.ipynb        : notebooks computing plots for part 3
```
Further precised comments can be found within each notebooks

And our report `report.pdf` summarizes our ideas.

## Requirements

Main Library needed
```
torch
networkx
matplotlib
```

## Getting started

Open jupyter notebooks inside the `notebooks` folder

```
jupyter notebook "NOTEBOOK-NAME"
```

Notebooks can be visited in the order given above in Description.
