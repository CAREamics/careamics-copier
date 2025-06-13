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