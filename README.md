# Instructions

## Create environment and run experiments
```
conda create --name WS_env python=3.8 
conda activate WS_env
pip install -r requirements.txt

bash run.sh # run bash file
```



## Dataset Source
| Name | Task | # class | # Prompted LFs | # train | # validation | # test | source
|:--------|:---------|:------|:---|:------|:-------|:-------|:--------------------|
| Spouse | relation classification | 2 | 11 | 22254 | 2811 | 2701 | [Github repo of Snorkel tutorial](https://github.com/snorkel-team/snorkel-tutorials/tree/master/spouse)| 
| Youtube | spam clasification | 2 | 10 | 1586 | 120          | 250    | [Google drive link shared in WRENCH benchmark](https://drive.google.com/drive/folders/19p_BsGsF_JuriiQV4RB6qH3wcZXcvWGa)| 
| SMS | spam clasification | 2 | 73 | 4571 | 500          | 500    | [Github repo of Snorkel tutorial](https://github.com/snorkel-team/snorkel-tutorials/tree/master/spam)| 

