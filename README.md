# Emotion__Recognition__From__Speech_-python-

##dataset
Berlin Database of Emotional Speech [1]
DaFeX Dataset [2-3]
Download Berlin DB from the link. Request DaFeX dataset following the link instructions. The code will generate automatically .wav files

Usage
Long option	Option	Description
--dataset	-d	dataset type
--dataset_path	-p	dataset path
--load_data	-l	load dataset data and info and save them into a .p file
--extract_features	-e	extract features from data and save them into a .p file
--speaker_indipendence	-s	cross validation is made using different actors for train and test sets
--plot_eigenspectrum	-i	show eigenspectrum for each training set
![image](https://github.com/user-attachments/assets/ab4b77a6-39b3-4dd0-8852-dfcf7b4067f6)



###Example:
python emorecognition.py -d 'berlin' -p [berlin db path] -e -l
The first time you run the application, -l and -e options are mandatory because you need to extract data and features. Every time you change the feature extraction method and/or the dataset data you need to specify -e and/or -l to update your .p files.
