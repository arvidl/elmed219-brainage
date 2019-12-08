# mmiv-kaggle-brainage
MMIV HealthHack 2019 - BrainAge Challenge


## Data description

From T1-weighted MR images of 1553 subjects we have calculated 143 features. These are collected in two CSV files: train.csv and test.csv (except those kept as a hidden test set used for the "Private leaderboard" score).

Your first task is to predict the age of the subjects in the test set.

For Part 2 of the challenge, where you're tasked with telling an interesting story about your data exploration and model results, you will likely have use for additional information about the subjects, including raw images. See here:

 - [SLIM](http://fcon_1000.projects.nitrc.org/indi/retro/southwestuni_qiu_index.html)

 - [SALD](http://fcon_1000.projects.nitrc.org/indi/retro/sald.html)

 - [IXI](https://sites.google.com/view/calgary-campinas-dataset/home)

 - [Calgary-Campinas](http://brain-development.org/ixi-dataset)

In the file `SLIM_longitudinal_info.csv` you will find data from 18 subjects scanned three times each, processed using the Freesurfer 6.0 longitudinal stream. This can be used to check robustness of your brainage models, and can be part of your "Part 2 story".

The feature names are a bit cryptic as they are from Freesurfer (6.0), which you may or may not be familiar with. We will give you a quick intro to Freesurfer during the challenge.

### Description of the files
 - `train.csv` - training data. Consists of subject ID, some basic subject information, morphometric data and labels (age)
 - `test.csv` - test data. Same features as in the training data, except no labels.
 - `sampleSubmission.csv` - an example of a submission file following the format accepted by Kaggle. You can use this to generate your own submission.
 - `SLIM_longitudinal_info.csv` - longitudinal data. Outputs from 18 subjects scanned three times.
