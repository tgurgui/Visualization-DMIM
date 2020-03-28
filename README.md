## DICOM 3D Medical Image Modeling (DMIM)

Nowadays, patients are sent to MRI, PET, and CT scans more than before. Each scan produces a large amount of information of a patient, normally as a set of 2D slices, that will be inspected by a doctor or a technician. The project aims to visualize any DICOM images by creating a 3D model in addition to the classic slice-by-slice inspection.

Demo:
https://www.youtube.com/watch?v=Xz3xwpmoMHg

&nbsp;
## Installation

This tutorial uses Conda and PIP. Please make sure to install them before you  proceed the next steps.

1. Create virtual environment with the following instruction:
```
$ conda create -f environment_mac.yml
```
This will create a new environment named “DMIM”.

2.  Activate the new DMIM environment by typing:
```
$ conda activate DMIM
```
3. Clone the repository and enter the directory:
```
$ git clone https://github.com/tgurgui/Visualization-DMIM.git
$ cd Visualization-DMIM/
```
4. Open new terminal window, create a folder for mongo data () and start MongoDB:
```
$ mongod
```
5. Finally, run the website from the repository main folder:
```
$ FLASK_APP=app.py FLASK_DEBUG=1 python -m flask run
```
6. The website should be available at http://localhost:5000/

A successful installation will result in the following index page:

<kbd>![Home Page](https://github.com/tgurgui/Visualization-DMIM/blob/master/static/wiki/4.jpg)</kbd>
&nbsp;&nbsp;

## More images from the app

#### Store and analyze various cases
<kbd>![Store and analyze various cases](https://github.com/tgurgui/Visualization-DMIM/blob/master/static/wiki/5.jpg)</kbd>
&nbsp;

#### 3D Analysis
<kbd>![3D Analysis](https://github.com/tgurgui/Visualization-DMIM/blob/master/static/wiki/8.jpg)</kbd>
&nbsp;

#### Slice Analysis
<kbd>![Slice Analysis](https://github.com/tgurgui/Visualization-DMIM/blob/master/static/wiki/10.jpg)</kbd>
&nbsp;

#### Draw on slices
<kbd>![Draw on slices](https://github.com/tgurgui/Visualization-DMIM/blob/master/static/wiki/11.jpg)</kbd>
&nbsp;&nbsp;


## References

The X ToolKit:
https://github.com/xtk/X

AMI:
https://github.com/FNNDSC/ami
