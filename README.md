# Quadcopter flying using RL

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/Kcsh/Quadcopter-learned-flying.git
cd /Quadcopter-learned-flying
```

2. Create and activate a new environment.

```
conda create -n quadcop python=3.6 matplotlib numpy pandas
source activate quadcop
```

3. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `quadcop` environment. 
```
python -m ipykernel install --user --name quadcop --display-name "quadcop"
```

4. Open the notebook.
```
jupyter notebook Quadcopter_Project.ipynb
```

5. Before running code, change the kernel to match the `quadcop` environment by using the drop-down menu (**Kernel > Change kernel > quadcop**). Then, follow the instructions in the notebook.

