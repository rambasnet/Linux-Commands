# LinuxCommand-Notebooks
Jupyter Notebooks to learn Linux Commands based on linuxcommand.org

## System Requirements
- Linux - Ubuntu or Kali (Debian)
- Miniconda https://conda.io/docs/user-guide/install/index.html for Python 3.
- git client

After installing miniconda, open a terminal and run the following commands; its easier if the notebook is ran as root.

```bash
conda update conda
conda install notebook
git clone <this repo>
cd <into the repo directory>
jupyter notebook --allow-root
```