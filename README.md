# Named Entity Recognition NER using spaCy ver3
Named Entity Recognition using CLI training process

## Repo includes folowing config files to train models:
```
-config_demo_acc (lg model based)
-config_demo_efficiency (train from empty)
-config_demo_transformer (trf model based)
```
*config files use wandb as logger 
*details about training and tests processes provided in NER_de_training.ipynb notebook

### Model usage
```
-trained models include best checkpoint (checkpoint setting can be changed in config files)
-to run model use "spacy.load(path_to_model)"
-in the repo provided smallest and simpliest model 
```
### Report plots
![Losses plot](reports/W&B Chart 01.08.2021, 14_50_21.png)
![Scores](reports/W&B Chart 01.08.2021, 15_08_16.png)

### Prerequisites
```
-spaCy
-sklearn
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
