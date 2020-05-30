# Example Database String Filtering Script
Example of a Script for filtering a DB: Remove strings atarting with Filt, keep first column only, and strip column names
The single column result will be written to the output file named "NewDatabase.txt"

Define filters to leave out of DB strings. Example: filt = ("Not", "Another", "Filter")

# filt = ([], [], [])

Define input file name and location for DB. Example: file = 'X:/XYZ/123/FILENAME'

# file = []

Default separator ";"

# base = pd.read_csv(file, sep=';')
