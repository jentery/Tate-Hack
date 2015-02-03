Modernist Faces 
=========

A collection of faces for a workshop in http://jentery.github.io/507/ at UVic. 

A fork of Terence Eden's Tate-Hack: https://github.com/edent/Tate-Hack. Thanks, Terence! And thanks, too, Philipp Wagner.

This script uses Python and runs images through OpenCV's face recognition.

If a face is detected in the Beinecke's "Picturing Literary Modernism" exhibit (http://beinecke.library.yale.edu/collections/highlights/picturing-literary-modernism), then the script crops the face and saves it as a separate image.  This will detect multiple faces per image. The images are saved in the "detected" subdirectory. The URLs for "Picturing Literary Modernism" exhibit are stored in all.txt.  

`downloadface.py` will crop the faces from ~30 images located at http://beinecke.library.yale.edu/collections/highlights/picturing-literary-modernism. (To add/remove URLs, simply edit all.txt.)

Run `python downloadface.py face.xml` to initiate the cropping. 

`eigensave.py` will generate an Eigenface model and save it to disk.

`recognise.py` will compare a photograph to the model and print out the nearest match.

Full write up, by Terence Eden, at http://shkspr.mobi/blog/2014/06/which-painting-do-you-look-like-comparing-faces-using-python-and-opencv/.
