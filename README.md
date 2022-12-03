# T5_human_intention_analysis

This repository is created to analyze the effect of human intentions in decision making during robot navigation task.

Overview : In this project, our aim is to leverage the power of human intentions in
helping a robot find objects in an unknown environment. First, we want to investigate if
these intentions will aid our robot in generalizing successfully to new environments, and
second, we want to know if this language component will enable us to train with fewer
samples than we could with only trajectory data.

The final goal is to compare the impact of using "language" and "not using language” on such a
model.

Link to the data we generated is: (https://drive.google.com/drive/folders/1lpgI1vjZrilxdvaHta71ZR-B8J-OuZax?usp=sharing)

Training: 

1. Make a copy for the data in your drive from the link above.
2. Use the script titled 'T5-TextGeneration_ActionPrediction.ipynb' which automatically loads the data from your Drive and 
   creates a dataloader of the tokenized text from the data.
3. Train the T-5 base model and you can tweak parameters like batch size, epochs and evaluation metric (currently we use 
   rogue score).
4. Test on your evaluation and test set.
5. See plots for model performance graphs in the tensorboard.



Give us a like if you find our work useful. 

Cheers!

