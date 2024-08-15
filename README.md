# AirSASBeamformingCode
This code is used to beamform and get a 2D image of data collected from the Air SAS setup

I have included test_run.zip, which contains the background and recording of data with a the selected object, so you may verify that the code works
I have also included the file which sets the parameter of the pixels, which creates the distribution of pixels to by 2 ft by 2 ft

If there are any issues with the code, I have provided some trouble shooting methods within the jupyter notebook as those were the most common issues I ran into. 

The code is broken up into 5 main subsections for clarity when dissecting the code. The 5 sections are: setup, LFM function, Group delay and backgound adjustments, 
and lastly beamforming. 
