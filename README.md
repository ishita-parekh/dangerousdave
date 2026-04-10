# dangerousdave
This project is on controlling dangerous dave game using hand getures. 

#Tech Stack used: Python and OpenCV

#General description:

This project makes use two concepts to detect the fingers and hence hand gestures: Convex hull and Covexity defects

1. Convex Hull: It is the convex boundary of an object. Where convex shape is the one in which interior angles are less than 180 and vice-versa is the concave shape. 

2. Convexity Defect: The regions not covered by the object in the convex hull around that object. A gap between a human finger is a convexity defect as two fingers are disjointed aka distinct convex contours. 

Game Control:

PyAutoGui python library is used to map laptop's keyboard controls to recognized hand gestures. 
