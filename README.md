Modernist Faces 
=========

A collection of faces for a workshop in http://jentery.github.io/507/ at UVic. 

A fork of Terence Eden's Tate-Hack: https://github.com/edent/Tate-Hack.

This script uses Python and runs images through OpenCV's face recognition.

If a face is detected, it crops the face and saves it as a separate image.  This will detect multiple faces per image.

`eigensave.py` will generate an Eigenface model and save it to disk.

`recognise.py` will compare a photograph to the model and print out the nearest match.

Full write up, by Terence Eden, at http://shkspr.mobi/blog/2014/06/which-painting-do-you-look-like-comparing-faces-using-python-and-opencv/
