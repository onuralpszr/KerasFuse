<h1 align="center">KerasFuse</h1>

<p>
  <img alt="GitHub" src="https://img.shields.io/github/license/ayyucedemirbas/Kerasfuse">
  <img alt="Python3" src="https://img.shields.io/badge/Python-3.8.1 | 3.9 | 3.10 | 3.11-3776AB.svg?logo=Python&logoColor=white"/>
  <img alt="Tensorflow" src="https://img.shields.io/badge/Tensorflow-v2.12.0-%23FF6F00.svg?logo=Tensorflow&logoColor=white"/>
  <img alt="Keras" src="https://img.shields.io/badge/Keras-v2.12.0-%23D00000.svg?logo=Keras&logoColor=white"/>
  <img alt="Black" src="https://img.shields.io/badge/code%20style-black-black"/>
  <img alt="isort" src="https://img.shields.io/badge/isort-checked-yellow"/>
</p>

KerasFuse is a Python library that combines the power of TensorFlow and Keras with various computer vision techniques for medical image analysis tasks. It provides a collection of modules and functions to facilitate the development of deep learning models in TensorFlow Keras for tasks such as image segmentation, classification, and more.

## Getting Started

### Installation

#### Poetry Installation

```bash
poetry install
poetry shell
```

#### Tip

If you have multiple Python versions on your system, you can set your Python version by using `poetry env` . Here's an example of how to use it:

```bash
poetry env use python3.10
```

More details at
[poetry-switching-between-environments](https://python-poetry.org/docs/managing-environments/#switching-between-environments)

#### Pip Installations

```bash
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt
```

For MacOS

```bash
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements-macos.txt
```

## License

This project is licensed under the terms of the GPL-3.0 license.
