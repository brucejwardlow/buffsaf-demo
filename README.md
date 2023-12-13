# Welcome to BuffSAF-Demo

BuffSAF is a python-based Simple Archive Format compiler meant to create bulk upload files for a D-Space Repository.

The Demo version is a simplified version of the program to make running the program easier for a novice. 

## Contents of this repository
- LICENSE
    - MIT License information
- README.md
    - The README that you are currently reading.
- buffalo-grazing-in-meadow.jpeg
    - One of the example images for the example metadata.csv.
- buffsaf-demo.html
    - This is the one file needed to run the unstable version without a python environment. 
- buffsaf-demo.py
    - This is the one file needed to  run this program in a python environment.
- metadata.csv
    - The example metadata.csv.
- mother-and-child.jpeg
    - One of the example images for the example metadata.csv.

term
: definition

## How to run BuffSAF

### HTML version - UNSTABLE

The HTML version of BuffSAF Demo is intended for use in justifications of getting a Python environment installed. With care, I've gotten it stable up to batches of 375 mb. 

This verion uses pyodide and [stlite](https://github.com/whitphx/stlite) to run fully in a client-side browser. 

To run this version: 

1. Click on BuffSAF-Demo.html
2. Click on the download icon in the top right corner.
3. Double click the .html file to run the program.
4. See additional documentation for instructions on how to use the program.

### Python Version - Simplified Version
 
install anaconda 3

open anaconda prompt

`pip install pandas` 
`pip install streamlit` 

`streamlit run buffsaf-demo.py`
