# RefiningModule

## Recreate Dataset containing weak labels from PromptedWS
```
conda create --name t0_env python=3.8 
conda activate t0_env
pip install -r requirements.txt
```

## Dataset Source
| Name | Task | # class | # LF | # train | # validation | # test | data source | LF source |
|:--------|:---------|:------|:------|:------|:-------------|:-------|:------|:------|
| Spouse | relation classification | 2 | 9 | 22254 | 2801         | 2701   | [link](http://ceur-ws.org/Vol-1568/paper8.pdf) | [link](https://arxiv.org/abs/1711.10160) |
| Youtube | spam clasification | 2 | 10 | 1586 | 120          | 250    | [link](https://archive.ics.uci.edu/ml/datasets/YouTube+Spam+Collection) | [link](https://github.com/snorkel-team/snorkel-tutorials/tree/master/spam) |
| SMS | spam clasification | 2 | 73 | 4571 | 500          | 500    | [link](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) | [link](https://openreview.net/forum?id=SkeuexBtDr) |








## Refining module
