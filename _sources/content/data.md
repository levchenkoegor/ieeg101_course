# Data Overview

## Datasets Used in This Course

Replace this section with descriptions of your specific datasets.

### Dataset 1 — [Name]

Describe the recording setup, task, number of subjects, electrode type, and
any preprocessing already applied.

:::{note}
Download instructions or a data access link go here.
:::

## Data Format

Describe the file format (EDF, NWB, BIDS-iEEG, etc.) and show how to load it:

```python
import mne

raw = mne.io.read_raw_edf('path/to/file.edf', preload=True)
print(raw.info)
```

## Directory Structure

After downloading, your data folder should look like:

```
data/
├── subject_01/
│   ├── ieeg.edf
│   └── channels.tsv
└── subject_02/
    ├── ieeg.edf
    └── channels.tsv
```
