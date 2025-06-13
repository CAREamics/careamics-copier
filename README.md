<p align="center">
  <a href="https://careamics.github.io/">
    <img src="https://raw.githubusercontent.com/CAREamics/.github/main/profile/images/banner_careamics.png">
  </a>
</p>

# CAREamics copier template

[![License](https://img.shields.io/pypi/l/careamics.svg?color=green)](https://github.com/CAREamics/careamics/blob/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/careamics.svg?color=green)](https://pypi.org/project/careamics)
[![Python Version](https://img.shields.io/pypi/pyversions/careamics.svg?color=green)](https://python.org)
[![Image.sc](https://img.shields.io/badge/Got%20a%20question%3F-Image.sc-blue)](https://forum.image.sc/)

The CAREamics copier template helps you build CAREamics scripts using intuitive prompting
in the console. The output is Python script that you can run to train and predict on 
your own data.

<p align="center">
  <img src="imgs/screenshot.png">
</p>

At the end of the process, you will have created the following files:
```
my_project_name/
└── experiment_name/
    ├── experiment_name.py
    └── config.yaml
```

Where `experiment_name.py` is the main script that you can run to train and predict on your data. The `config.yaml` file contains the configuration for the experiment, which you can reuse in other contexts (e.g. with similar data).

## How to use CAREamics copier template

1. Install [CAREamics](https://careamics.github.io) in an environment.
2. Install [copier](https://copier.readthedocs.io/en/stable/) and black.
    ``` bash
    pip install copier black
    ```
3. Run copier with the CAREamics template.
    ``` bash
    copier copy gh:CAREamics/careamics-copier my_project_name
    ```

## Run the generated script

If your paths are correct, you can simply run the generated script with:
```bash
python my_project_name/experiment_name/experiment_name.py
```

Where `my_project_name` is the name you provided when running copier, and `experiment_name` is the name of the experiment you entered during the prompting process.

## The script does not work, what should I do?

First and foremost, make sure that the paths to your data are correct in the python script. You can modify them after the script has been generated.

If you encounter any issues with the generated script, please open an [issue](https://github.com/CAREamics/careamics-copier/issues).