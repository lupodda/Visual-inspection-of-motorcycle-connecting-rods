# Visual-inspection-of-motorcycle-connecting-rods

The aim of the project is to develop a software system aimed at visual inspection of motorcycle connecting rods.
The system must be able to analyze different types of gray-scale images containing connecting rods and provide information about each rod which appears:

* Type of rod: one hole (type A), two holes (type B)
* Position and orientation
* Length, width and width at the barycenter
* Position of the center and diameter of each hole

## Image features

All images have been taken by the backlighting technique, so that rods are easily distinguishable from the background. However, other factors must be considered:

* The power of the lighting source may change
* The inspection area may be dirty due to the presence of scattered iron powder

## Requirements

In order to successfully reproduce the results on ````visual_inspection.ipynb```` notebook, the following installations are required:

* [Python](https://www.python.org/)
* [NumPy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [OpenCV](https://pypi.org/project/opencv-python/)
