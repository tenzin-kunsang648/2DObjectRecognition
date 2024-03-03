# Real-time 2-D Object Recognition
## Tenzin Kunsang 
## Purpose: Real-time 2-D Object Recognition
### Date : Feb 23rd, 2024

Usage:
./2dor 'a' # for Threshold + Clean up + region segmentation
./2dor 'b' 'object label' # for feature vectorization of training examples and storing in a database
./2dor 'c' k_value # classification of a new image against training images' feature vectors in the database, k defaulted to 1 if not given
