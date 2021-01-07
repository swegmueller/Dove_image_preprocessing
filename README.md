# Dove_image_preprocessing
Python tools for pre-processing Dove imagery. This files are fairly informal and uploaded just to 
help those who may need them. 

Planet_masking_udm_and_udm2 is a Jupyter notebook for masking a Dove image using the included
UDM an UDM2 files.  Feel free to download and edit as needed. 

Planet_masking_whole order does the same thing as Planet_masking_udm_and_udm2, but is set up to do
an entire order from Planet Explorer (not sure if this will work with order via the API -- haven't
tested it yet).  I'm lazy and I like efficiency... 

TopoCorrectionClass is a class I wrote to make topographical correction of Dove imagery easy. 
Also in a Jupyter notebook, the class is on top and the use is underneath it. Selected references
to the methods are in the code. I didn't create these methods -- I just coded them for Dove imagery.  
I've also included code for reprojection and resampling to be done automatically as needed.
