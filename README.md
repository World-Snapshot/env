# WSM v1 Environment

This repository contains the dependency definitions for **World Snapshot Model v1 (WSM v1)**.

From the root of the WSMs repository, create and install the environment with:

```bash
conda create -n WSM python=3.11 -y
conda activate WSM
pip install -r WSM_v1/env/requirements.txt
```

`requirements.txt` is the maintained dependency list. `wsm_export_packages.txt`
records a complete package snapshot from a working WSM v1 environment for
reproducibility and debugging.
