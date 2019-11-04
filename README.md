# python-finance-trading

## Setup & Installation

- Downloading Anaconda - https://www.anaconda.com/distribution/
- Setup Environment
- Working with Jupyter Notebook

In case you don't want to install Anaconda:

```
pip install jupyter
```

Conda Environments:
https://conda.io/projects/conda/en/latest/user-guide/concepts/environments.html#share-an-environment

Create Anaconda Environment

**environment.yml**
```yml
name: pyfinance
channels:
- defaults
dependencies:
- cycler
- icu
- jpeg
- libpng
- matplotlib
- mkl
- numpy
- openssl
- pandas
- pandas-datareader
- patsy
- pip
- pyparsing
- pyqt
- python
- python-dateutil
- pytz
- qt
- requests
- requests-file
- requests-ftp
- scipy=0.19.1
- setuptools
- sip
- six
- statsmodels
- tk
#- vs2015_runtime
- wheel
- zlib
- pip:
  - certifi
  - chardet
  - idna
  - inflection
  - more-itertools
  - quandl
  - urllib3
prefix: \\Anaconda3\envs\pyfinance
```

```
conda env create -f environment.yml
```

```
source activate pyfinance
```

```
jupyter noteboook
```
