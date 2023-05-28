# Decoding Semantics - Imagined and Perceived Categories from EEG data


## Overview

#### Dataset
The dataset used in this tutorial can be downloaded from OpenNeuro respository <https://openneuro.org/datasets/ds004306/versions/1.0.0>. It includes 12 participants who in each session imaginined and perceived stimuli from three modalities; visual pictorial, visual orthographic (writing) or auditory. Each of the stimuli belonged to one of three categories: guitar, flower and penguin. These categories were selected based on being semantically dissimilar to one another, and because there were all of 2 syllables. The dataset can be downloaded as raw continuous data or the pre-processed version. A script is provided for converting the data into epochs.

#### Code
The following code can be used to pre-process, perform technical validation as described in the publication ***, and as a starter to perform classification based decoding on the dataset.

The code is written in tutorial style, using jupyter notebook. The main script 'batch-papermill' can be used to run automate scripts for all participants, or alternative each file can be run with locally selected parameters such as participant and task.

#### Extra files
meta_extended.csv contains participant information such as what cap size was used, and channels that were manually identified as being bad
