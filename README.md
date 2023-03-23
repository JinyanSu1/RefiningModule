# RefiningModule

## Recreate Dataset containing weak labels from PromptedWS
```
conda create --name t0_env python=3.8 
conda activate t0_env
pip install -r requirements.txt
```
The datasets can be downloaded via [this](https://drive.google.com/drive/folders/1NbK7gq3pPn6HKy6CTF7pI3ivrHUT5kfR?usp=sharing).
## Dataset Source
| Name | Task | # class | # Prompted LFs | # train | # validation | # test | source
|:--------|:---------|:------|:------|:------|:-------|:-------|:--------------------|
| Spouse | relation classification | 2 | 9 | 22254 | 2811 | 2701 | [Github repo of Snorkel tutorial](https://github.com/snorkel-team/snorkel-tutorials/tree/master/spouse)| 
| Youtube | spam clasification | 2 | 10 | 1586 | 120          | 250    | [Google drive link shared in WRENCH benchmark](https://drive.google.com/drive/folders/19p_BsGsF_JuriiQV4RB6qH3wcZXcvWGa)| 
| SMS | spam clasification | 2 | 73 | 4571 | 500          | 500    | [Github repo of Snorkel tutorial](https://github.com/snorkel-team/snorkel-tutorials/tree/master/spam)| 






## Refining module
