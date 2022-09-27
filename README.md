# Cross-lingual transfer of resources and models for question answering

Repository for master's thesis @ Faculty of Computer and Information Science, University of Ljubljana.

## Installation
Dependencies:
- `python==3.7.13`
- `torch==1.9.1+cu111`
-  [jiant](https://github.com/nyu-mll/jiant.git)

## Usage

For using the translation notebook you need to add Google Cloud Translation API credentials first (in the file *translation_api_credentials.json*).

The model training and evaluation is done within the toolkit [Jiant](https://github.com/nyu-mll/jiant.git). Jiant is an open-source Python toolkit for natural language understanding tasks.
The notebooks for fine-tuning QA models in Macedonian were used in Google Colab (due to lack of computational resources). The code is not tested in other environments.

## Datasets

This project uses three QA datasets from the SuperGLUE benchmark: BoolQ, COPA and MultiRC. The semi-automatic translation of SuperGLUE in Macedonian can be accessed [here](https://drive.google.com/drive/folders/1-8hLfW14D5lWz5g7jMzYNLR-DzMynlFR?usp=sharing).
