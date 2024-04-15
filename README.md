# CapstoneProject - Diseases Prediction

### Introduction:
We aim to create a model to assist healthcare providers with patients’ diagnoses.

For now, we have implemented different models to be trained on the ground truth pathology. Please refer to `predict_pathology` folder.

### Requirments:
![requirements](https://img.shields.io/badge/Python->3.8.0-3480eb.svg?longCache=true&style=flat&logo=python)
```
pip install -r requirements.txt
```
Note: By default, CPU version of Pytorch is installed. If you like to use GPU version, please refer to https://pytorch.org/.

Or try following command after installing requirements.txt:
```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

### Data source: 
[DDXPlus: A New Dataset For Automatic Medical Diagnosis](https://arxiv.org/pdf/2205.09148.pdf) 
and [its data](https://figshare.com/articles/dataset/DDXPlus_Dataset/20043374)

Please download and place the data in `data` folder

### Citation:
```
Fansi Tchango, A., Goel, R., Wen, Z., Martel, J., & Ghosn, J. (2022).
Ddxplus: A new dataset for automatic medical diagnosis.
Advances in Neural Information Processing Systems, 35, 31306-31318.
```
