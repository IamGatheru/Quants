# Python for Data Analysis

## Prelims

### Download and install Miniconda.

<code>curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh</code>

### Create an executable.

<code> chmod u+x Miniconda3-latest-linux-x86_64.sh</code>

### Run the executable
<code> ./Miniconda3-latest-linux-x86_64.sh</code>


## Create a new conda environment

<code> conda create -y -n quant python=3.10 </code>

To activate the environment, run:

<code> conda activate quant </code>

Miniconda is a minimalist version of [Anaconda](https://www.anaconda.com/download). To use libraries, pandas and the like, run <code> conda install pandas ... </code> command.

Here's a list of all the libraries i will be using in this repository:

<code> conda install pandas ipython numpy scikit-learn jupyter lxml beautifulsoup4 html5lib requests sqlalchemy seaborn scipy statsmodels patsy pyarrow pytables numba </code>

You can update packages using the <code> conda update </code> command.

<code> conda update package_name </code>

pip also supports upgrades using the <code> --upgrade</code> flag:

<code> pip install --upgrade package_name </code>

#### Packages installed via conda should not be upgraded via pip lest package conflicts may arise.
