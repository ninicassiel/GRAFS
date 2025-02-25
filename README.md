- **\GRAFS\code\stage1** holds the code for the first stage, run `python train_local.py` to train model fusing FCN and SCN by reconstrution graph structure.
- **\GRAFS\code\stage2** holds the code for the second stage, run `python train_local.py` to train model for A��-PET prediction.
- **\GRAFS\code\stage1\visual.py** can visualize the graph reconstruction results.
- **\GRAFS\data** provides data from several in-house subjects for training and testing purposes. Both the FCN, SCN, and regional PET SUVR are obtained using the Schaefer 2018 atlas with 100 ROIs.