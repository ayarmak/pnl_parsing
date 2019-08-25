# Profit & Loss Statement Parsing
*A Udacity Machine Learning Nanodegree capstone project "Parsing P&amp;L statements from financial reports"*

In this project, I have designed a workflow to download a set of annual reports from EDGAR website, pre-process them for parsing Profit & Loss statements, and train the machine learning models to enable automatic parsing.

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/ayarmak/pnl_parsing.git
cd pnl_parsing
```

2. Create and activate a new environment.

```
conda create -n pnl_parsing python=3.6.3
source activate pnl_parsing
pip install -r requirements.txt
```

3. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `pnl_parsing` environment. 
```
python -m ipykernel install --user --name pnl_parsing --display-name "pnl_parsing"
```

4. Open Jupyter Notebook to see the list of project notebooks.
```
jupyter notebook
```

5. Before running code, change the kernel to match the `pnl_parsing` environment by using the drop-down menu (**Kernel > Change kernel > quadcop**). Then, follow the instructions in the notebook.

