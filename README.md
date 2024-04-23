# Hugging Face Transformers Usage Practice

## Overview
This repository serves as a practice space for using the Hugging Face Transformers models in various ways on different NLP tasks. With the `Pytorch` DL framework. 
## From Higher to Lower
- **[Higher](./highest_level.ipynb)**: By using the **pipeline** high-level API.
- **[Mid](./mid_level.ipynb)**: By using the **AutoTokenizer**, **AutoModel** and **torch**.
- **[Lower](./lower_level.ipynb)**: By using `tokenize`, `convert_tokens_to_ids`, `pad_token`, `attention_mask`, `ids to tensors (ids to input_ids)` and `softmax`.

## Usage
1. Clone this repository to your local machine:
```zsh
git clone git@github.com:IsmaelMousa/playing-behind-pipeline.git
```
2. Navigate to the **playing-behind-pipeline** directory:
```zsh
cd playing-behind-pipeline
```
3. Setup virtual environment:
```zsh
python3 -m venv .venv
```
4. Activate the virtual environment:

```zsh
source .venv/bin/activate
```
5. Install the required dependencies:

```zsh
pip install -r requirements.txt
```