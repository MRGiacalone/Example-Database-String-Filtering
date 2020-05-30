# Example Database String Filtering Script
The file DB Filter Script.py is an example of a script for to: Remove all strings starting with the words defined in Filt, keep first column only, and strip column names. The single column result will be written to the output file named "NewDatabase.txt"

In the script you should:

Define filters to leave out of DB strings. Example: stringFilter = ("Not", "Another", "Filter")
# stringFilter = ([], [], [], etc)

Define input file name and location of DB. Example: fileInput = 'X:/XYZ/123/FILENAME'
# fileInput = []

Define output path and file name. Example: fileOutput = 'X:/XYZ/123/NEWFILENAME'
# fileOutput = []

Default separator ";"
# base = pd.read_csv(fileInput, sep=';')
