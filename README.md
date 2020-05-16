# CondNet

Copyrights (c) 2020, Essam Rashed 
(essam (dot) rashed (at-sign) nitech.ac.jp), NITech, Nagoya, JP 

This code aims at mapping (T1/T2) MRI images with dielectric properties (e.g. conductivity & permittivity). 

This code is compatible with Mathematica 12.0 and beyond and tested over Windows 10, Ubuntu 16.04, and OSX 10.11.6. More details are in our papers mentioned below. If you are using this code, please cite our papers.

-> Input images are in MATLAB "*.mat" formats for easy use

-> To Run Select Evaluation -> Evaluate Notebook

-> If you are not familier with Mathematica Notebooks (*.nb), you can download free reader from here: http://www.wolfram.com/cdf-player/

"CondNet.nb"

This notebook will train the CondNet architecture to estimate dielectric properties. . Input: MRI images (T1 & T2), labels of Conductivity, Permittivity, and Tissue Densiy Output: Trained Network + loss function (training/validation) values

"Test_All.nb"

This notebook will use a pretrained network to estimate diectric properties. 

Other files

"parameters.nb" -> Parameters & settings

"arch01.nb" -> Network architecture (called automatically)

"Read_train_T1.nb" -> upload the files for network training in (T) Transaxial direction

"Test_T1.nb" -> network evaluation (test) for single subject in (T) direction

How to use

Open in Mathematica (12.0 or above), Evalute -> Evaluate Notebook

References
==========
* E. A. Rashed, Y. Diao and A. Hirata, "Learning-based estimation of dielectric properties and tissue density in head models for personalized radio-frequency dosimetry," Physics in Medicine and Biology, 2020 (doi: https://doi.org/10.1088/1361-6560/ab7308)

* E. A. Rashed, J. Gomez-Tames and A. Hirata, "Deep learning-based development of personalized human head model with non-uniform conductivity for brain stimulation," IEEE Transactions on Medical Imaging, 2020 (doi: https://doi.org/10.1109/TMI.2020.2969682)
