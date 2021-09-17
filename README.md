# GAS-ssg
 Gus' Awesome SSG


Instructions: 

-Compile using c++std=17 in your compiler of choice
-Run with command line options:
   
   -i or --input to specify a file or folder to be converted
    i.e "gas -i ./folder" OR "gas --input abacus.txt"
    
   -h or --help to get info on command line arguments possible
    i.e "gas -h"
    
   -v or --version to get version information
    i.e "gas -v"
    
-Will convert any txt files to html or recursively search through folders to find txt files to convert to html (Optional feature 1)
-Files will be placed in ./dist/ folder, will overwrite existing ./dist/ folder
-Title will be generated if first line is followed by two blank lines (Optional feature 2)
