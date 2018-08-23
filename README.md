# emotion-change-seq2seq
An tensorflow program to create emotion labels for audio data for every half second
Inputs are made static.
Emo folder contains audio files with emotions labelled by folder name make_data_from _emo.ipynb is a jupiter notebook file to create audio files(freely available, in german language) by appending at most 3 files files from emo folder and creates a data for inputs containing mfcc of the audio and sequence of emotion labels for every half second for each file. The data is stored in a large padsample.pickle file that is used as training and testing data for the jupyter notebook train_and_check.ipynb emotion labels are numbers corresponding to numbers inthe folder names in emo folder, 0 is for no sound.
