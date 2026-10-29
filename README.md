This repository provides code for *The Traveling Bandit: A Framework for Bayesian Optimization with Movement Costs*.

We propose a framework for Bayesian optimization (BO) with movement costs, in which the designs within each batch are visited in the order given by a Traveling Salesman Problem, reducing the cost of moving between inputs.


Below is an instruction on how to set up the required environment. First, please open Anaconda Powershell. Locate this folder set it as the workspace by 

```
cd YOUR_PATH\THIS_REPOSITORY
```

Next, create a fresh environment using the following code and respond y to all prompts:

```
conda create --name travelbo python=3.12.11
```

Before activating the new environment, make sure to deactivate the base:

```
conda deactivate
```

Activate the new environment:

```
conda activate travelbo
```

You should now be in the (travelbo) environment. Now, install the required packages:

```
pip install -r requirements.txt
```

To reproduce a figure of a specific test function, first go to the corresponding directory. For example, for Griewank, you will use 

```
cd 2d_Griewank
```


Then, run:

```
python figure.py
```

The output will be saved under 2d_Griewank/Figures folder.

## Citation

[Paper](https://doi.org/10.1080/00401706.2025.2573228) (Technometrics, 2026). If you use this code, please cite:

```bibtex
@article{chen2026traveling,
  title={The Traveling Bandit: A Framework for {B}ayesian Optimization with Movement Costs},
  author={Chen, Qiyuan and Al Kontar, Raed},
  journal={Technometrics},
  volume={68},
  number={2},
  pages={239--250},
  year={2026},
  doi={10.1080/00401706.2025.2573228}
}
```
