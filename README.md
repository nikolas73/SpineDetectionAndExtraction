## Spine Detection and Extraction
This code segments, detects and extracts
 the spines from three dimensional 
  _in vivo_ images of dendrites with spines. 

## Usage
Clone or downlaod the repository and run
_AutomatedSpineExtractionModule.m_to get
 the segmented image, centerline of the 
 image, detected endpoints, roughly extracted
 spines and spine count.
 
## Visualization
Download and install ParaView
[ParaView](http://www.paraview.org/download/). 
To visualize the 3D image ("Test_Volume" in 
the directory "Data"):

 1. Open .mhd
("Test_Volume.mhd") file.
 2. Press 
"Apply". 
 3. From the drop-down of  "Representation", choose
"Volume". 

To visualize any binary image
generated by the code (for example, the 
segmentation of the image, or extracted 
spines):

   1. Open the .mhd file(s)
   2. Press "Apply". 
   3. From the "Filters" tab, use "Alphabetical" 
    list and select "Iso Volume".
   4. In the section 
"Input Scalars", change "Minimum" to something 
greater than zero and less than 1.
   5. Press "Apply".



#### Contributions
The segmentation code was developed by 
Paul Hernandez Herrera and the centerline 
generation code was developed by David Jiménez.

#### Data
Thanks to Sajo M and  Morishita H, Department 
of Psychiatry, Department of Neuroscience, 
Department of Ophthalmology, Mindich Child 
Health and Development Institute, and 
Friedman Brain Institute, Icahn School 
of Medicine at Mount Sinai, New York.

