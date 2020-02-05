# To-Make-Blackboard-Notes-Visual-Friendly
This is a simple algorithm for processing photos of blackboard notes. It allows users to convert photos into an easy-to-print form.
## Environment
MATLAB R2019a-academic use
## Function
The photos of blackboard notes usually have a dark background, which makes them blur when printed out. This simple 11-row program can convert the photots into a much clearer form.
Run 'main.m' in MATLAB. It will read in all the jpg images in the current folder, process them, and save the processed images in the current folder with '_result' suffix.
## Program Flow
1. Read all images.
2. Extract background which contains brightness distribution using 'ordfilt2'.
3. Subtract this background from the original image.
4. Binarization.
## Demo
