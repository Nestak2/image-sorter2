# image-sorter2
One-click image sorting/labelling script. Copies or moves images from a folder into subfolders.

<img width="700" alt="pic_github_readme" src="https://user-images.githubusercontent.com/16193553/53246066-89bfd680-36a7-11e9-9eaf-9adee0b8efa1.png">


This script is intended to be a help for users sorting a set of mixed images into folders differentiated by classes - e.g. cats image folder, dog images folder, bikes images folder a.s.o. The script launches a GUI which displays one image after the other and lets the user give different labels, corresponding to different folders, from a list provided as input by the user. In contrast to original version, version 2 allows for relabelling and keeping track of the labels. Provides also short-cuts - press "1" to put into "label 1", press "2" to put into "label 2" a.s.o.

## Usage:

Ensure tk is installed, e.g. 'sudo apt-get install python3-tk' See: https://tkdocs.com/tutorial/install.html
run 'pip install -r requirements.txt' to install dependencies. 

then

run 'python sort_folder_vers2.py' or copy the script in a jupyter notebook and run then. You need also to provide your specific input in the file-header (source folder, labels, 'copy' or 'move' mode, path to tracker file, desired file extensions (.jpg, .png, ...), resize keeping original aspect ratio or display original). Read the header in the .py-script, follow the discriptions and make the necessary changes to run it on your machine.

## Other useful scripts:
A list of other image labelling/sorting script that might be helpful

https://github.com/NaturalIntelligence/imglab

https://github.com/opencv/cvat

https://github.com/Cartucho/OpenLabeling

https://github.com/JNingWei/Image_Algorithm_Toolbox

https://play.google.com/store/apps/details?id=co.slidebox

### Authors:
original Author: Christian Baumgartner (c.baumgartner@imperial.ac.uk),
see here original "image-sorter" code: https://github.com/baumgach/image-sorter

changes, version 2: Nestor Arsenov (nestorarsenov_AT_gmail_DOT_com), created at London Center for Nanotechnology with project funding provided by The Foundation for Innovative New Diagnostics (FIND)

Date: 22. Feb 2019
