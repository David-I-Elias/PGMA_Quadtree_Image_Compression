# PGMA_Quadtree_Image_Compression
This script takes a given pgma file and compresses it using a quadtree algorithim.
Included is a sample 'baboon.pgma' image for testing.

USAGE:
Script takes the following arguments: file_name, variance_threshold

Example usage in command line:  python main.py baboon.pgma 4
this command will run the quadtree algorithim on the baboon.pgma file with a variance threshold of 4

NOTE:
This script only processes pgma files using the magic number 'P2'. Source code must be edited to allow 
other magic numbers to work.


