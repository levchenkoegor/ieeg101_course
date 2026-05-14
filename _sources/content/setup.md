# Software & Setup

## Python Environment

We recommend [conda](https://docs.conda.io/) (via Miniconda) to manage your
Python environment. Python 3.9 or later is required.

```bash
conda create -n ieeg python=3.11
conda activate ieeg
```

## Required Packages

```bash
pip install mne numpy scipy matplotlib pandas jupyter
```

A `requirements.txt` is provided in the repository — run
`pip install -r requirements.txt` to install everything at once.

## Running Notebooks Locally

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
jupyter lab
```

## Google Colab (no installation)

Every tutorial page has an **Open in Colab** button in the top bar.
Click it to run the notebook entirely in the cloud.

:::{tip}
If you use Colab, run this cell at the top of each notebook to install
dependencies:
```text
!pip install mne numpy scipy matplotlib -q
```
:::
