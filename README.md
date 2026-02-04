# HW_2_CV
Home Work #2  Computer Vision

1.  For this homework you will have to complete and implement the colour balancing for:

Gray world algorithm
Scale-by-max algorithm
You are free to use your own images. Experiment with more images and think about the effect each of the algorithms has on the resulting (balanced) image.

Colour Balancing
In this notebook we will show different type of colour balancing making use of von Kries' hypothesis.

2. White patch
In white patch algorithm we choose a group of pixels we know they should be white. We then scale the resulting image colour channels by this white patch.
Define white patch and the coefficients
Apply white balancing and generate balanced image
White patching does not guarantee that the dynamic range is preserved, images must be clipped.

3.	Gray world
This algorithm assumes that a scene, on average, is gray.
Compute the mean values for all three colour channels (red, green, blue)
Compute the coefficients kr, kg, kb
Note: there are 3 coefficients to compute but we only have 2 equations.
Therefore, you have to make an assumption, fix the value of one of the
coefficients and compute the remining two
Hint: You can fix the coefficient of the brightest colour channel to 1.
Apply color balancing and generate the balanced image
Show the original and the balanced image side by side

4. Scale-by-max
This is a straightforward algorithm that scales each colour channel by its maximum value. Note that it is sensitive to noise and saturations.
Load your image
Compute the maximum values for all three colour channels (red, green, blue)
Apply scale-by-max balancing and generate the balanced image

