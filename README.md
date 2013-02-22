MergeScript
===========

Function: 
MergeScript.py goes through all the text files within a directory specified by the user
and appends the results in ascending order (currently only numerically) to another text file.

MergeScript.py is currently made to stop every two text files it parses based on the needs
of the user. 

For more information or support regarding modding this script, visit the Office Scripts 
subreddit. 

Important Notes: 
The first (title) line of every input text file is ignored. 

Usage: 
Input is taken through the command line (same MO for all operating systems)

$$python MergeScript.py -s <source directory> -d <output directory destination> -st <first of the input files>

The last argument will be the full path to any file in your input directory. 

Sample Input File Format

Vernonica.txt
Image Number   Lower Angle   Upper Angle    Accessibility Level
6340          -22.97          14.61                 2
7357          16.69          10.95                 2
6847          13.15          7.87                 2
7876          14.86          9.76                 2
5828          1.88          0.88                 4

NewFile.txt
Sample Output of the above snippet:
5828          1.88          0.88                 4
6340          -22.97          14.61                 2
6847          13.15          7.87                 2
7357          16.69          10.95                 2
7876          14.86          9.76                 2



