# spyral_notebooks

This repository is a collection of notebooks for use with the ATTPC Spyral analysis library. Included are notebooks which allow you to inspect each of the default Phases of Spyral and see what is actually happening under the hood. These notebooks are great for testing out new configurations and new datasets.

## Setup and Install

First download the repository using

```bash
git clone https://github.com/ATTPC/spyral_notebooks.git
```

Then, create a virtual environment using your Python distribution inside of the repository. Note Spyral requires you to use Python >= 3.10. Creating a virtual environment can be done using

```bash
python -m venv .venv
```

Then activate your environment using

```bash
source .venv/bin/activate
```

This works on MacOS and Linux. On Windows slightly different commands should be used. Now you can install the required dependencies using

```bash
pip install -r requirements.txt
```

## Usage

It is recommended to use Jupyter Lab. To run Jupyter Lab use the command

```bash
jupyter-lab
```

Make sure that you have the virtual environment active when doing this! You can also run the notebooks through some IDE's (such as VSCode) with the proper extensions installed.
