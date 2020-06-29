![alt text](https://github.com/MDFahimAnjum/EEGProjectDataProcess/blob/master/guide/Banner.jpg?raw=true)

This is a Matlab Toolbox for importing raw EEG data onto Matlab. There are two tools in this toolbox. **Data Importer** and **Data Organizer**

# Requirements: 
* Matlab
* EEGLab toolbox for Matlab  [link to EEGLab!](https://sccn.ucsd.edu/eeglab/download.php)

# Data Importer 
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/logo1.PNG?raw=true)

This tool is used for obtaining .mat files from .eeg and .vhdr files.
## Guide
1. make sure you have EEGlab
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/step0.png?raw=true)

1. Select the file *standard-10-5-cap-385.elp* from the EEGLab installation location. 
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/stepa1.png?raw=true)

1. Select the .VHDR files you want to import. 
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/stepa2.jpg?raw=true)

1. Select the location where the .mat files will be saved
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/stepa3.jpg?raw=true)

1. Click **Start** to initiate the conversion.

# Data Organizer 
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/logo2.PNG?raw=true)

This tool is used for Collecting the imported EEG data in different .mat files into a single .mat file.
This tool takes converted EEG data between two groups of set. One set is named as *control* and the other one is *PD*.
This tool will provide a single .mat file with the EEG data of these two sets in two cell.   
## Guide

1. Select the *.mat* file for the first group (Controls). 

![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/stepb1.png?raw=true)

1. Select the *.mat* file for the second group (PD). 
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/stepb2.png?raw=true)

1. Select the location where the .mat file will be saved
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/stepb3.jpg?raw=true)

1. Select the name of the .mat file

![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/stepb4.png?raw=true)

1. Click **Start** to initiate the conversion. It will notify the completion with a dialogue box. 
![alt text](https://github.com/MDFahimAnjum/EEG-Data-Processing-Toolbox/blob/master/guide/stepb5.png?raw=true)

