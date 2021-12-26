# Graph-To-Text Generation (Pending)
Text Generation from Graphical Data using Pre-Trained LM (GPT2 & T5).
Use Following Methods (References):
* Fine-Tuning
* Prefix-Tuning ([Li and Liang](https://arxiv.org/abs/2101.00190), 2021)
* Control Prefixes ([Clive et al.](https://arxiv.org/abs/2110.08329), 2021)

My Own Reviews (Korean): [Blog](https://chainsmokers.oopy.io/)
### Dependencies
* jupyter
* pytorch
* transformers
* nltk
### Usage
```bash
git clone https://github.com/ChainsmokersAI/Graph-To-Text.git
cd Graph-To-Text
mkdir model generation
# Run Jupyter(.ipynb) Files
```
## Datasets
### WebNLG
* Generate Text Corresponding to RDF Triples
* Import from Prefix-Tuning [Repo](https://github.com/XiangLi1999/PrefixTuning/tree/cleaned/data/webnlg_challenge_2017)
* How to Process: [/EDA/WebNLG.ipynb](https://github.com/ChainsmokersAI/Graph-To-Text/blob/main/EDA/WebNLG.ipynb)
## Models
Training and Evaluation (Generation: Beam Search)
### GPT2
* Fine-Tuning ([Code](https://github.com/ChainsmokersAI/Graph-To-Text/blob/main/notebook/GPT2/FineTune.ipynb))
* Prefix-Tuning ([Code](https://github.com/ChainsmokersAI/Graph-To-Text/blob/main/notebook/GPT2/PrefixTune.ipynb))
* Control Prefixes ([Code](https://github.com/ChainsmokersAI/Graph-To-Text/blob/main/notebook/GPT2/ControlPrefixes.ipynb))
### T5
* Fine-Tuning ([Code](https://github.com/ChainsmokersAI/Graph-To-Text/blob/main/notebook/T5/FineTune.ipynb))

