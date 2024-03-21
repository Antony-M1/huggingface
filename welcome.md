
# Welcome

your going see how to use the hugging Face

### Getting started with our git and git-lfs interface

**You can create a repository from the CLI (skip if you created a repo from the website)**

```cmd
pip install huggingface_hub
```
You already have it if you installed transformers or datasets
```
huggingface-cli login
```
Log in using a token from huggingface.co/settings/tokens
Create a model or dataset repo from the CLI if needed
```
huggingface-cli repo create repo_name --type {model, dataset, space}
```

**Clone your model, dataset or Space locally**
Make sure you have git-lfs installed
(https://git-lfs.github.com)
```
git lfs install
```
```
git clone https://huggingface.co/username/repo_name
```
