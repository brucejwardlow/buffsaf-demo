# Welcome to BuffSAF-Demo

[BuffSAF](https://github.com/brucejwardlow/BuffSAF) is a python-based Simple Archive Format compiler meant to create bulk upload files for a D-Space Repository.

The Demo version is a simplified version of the program to make running the program easier for a novice. 

## Contents of this repository
- [LICENSE](https://github.com/brucejwardlow/buffsaf-demo/blob/main/LICENSE)
: MIT License information
- [README.md](https://github.com/brucejwardlow/buffsaf-demo/blob/main/README.md)
: The README that you are currently reading.
- [buffalo-grazing-in-meadow.jpeg](https://github.com/brucejwardlow/buffsaf-demo/blob/main/buffalo-grazing-in-meadow.jpeg)
: One of the example images for the example metadata.csv.
- [buffsaf-demo.html](https://github.com/brucejwardlow/buffsaf-demo/blob/main/buffsaf-demo.html)
: This is the one file needed to run the unstable version without a python environment. 
- [buffsaf-demo.py](https://github.com/brucejwardlow/buffsaf-demo/blob/main/buffsaf-demo.py)
: This is the one file needed to  run this program in a python environment.
- [Documentation]()
: This is the additional documentation on how to install and use the script.
- [metadata.csv](https://github.com/brucejwardlow/buffsaf-demo/blob/main/metadata.csv)
: The example metadata.csv.
- [mother-and-child.jpeg](https://github.com/brucejwardlow/buffsaf-demo/blob/main/mother-and-child.jpeg)
: One of the example images for the example metadata.csv.



## How to run BuffSAF

### HTML version - UNSTABLE

The HTML version of BuffSAF Demo is intended for use in justifications of getting a Python environment installed. With care, I've gotten it stable up to batches of 375 mb. 

This verion uses [pyodide](https://github.com/pyodide/pyodide) and [stlite](https://github.com/whitphx/stlite) to run fully in a client-side browser. 

To run this version: 

1. Click on BuffSAF-Demo.html
2. Click on the download icon in the top right corner.
3. Double click the .html file to run the program.
4. See [additional documentation]() for instructions on how to use the program.

### Python Version

This is the fully functional, stable version currently in production use at West Texas A&M University. 

There is a version with more features available at [BuffSAF](https://github.com/brucejwardlow/BuffSAF), however that version is still in development and has a much more complex installation process and less documentation. 
 
To run this version: 

1. Install a python environment. (I recommend [Anaconda](https://www.anaconda.com/))
2. Open python prompt.
3. Install pandas using the following prompt:  
    `pip install pandas`
4. Install streamlit using the following prompt:      
    `pip install streamlit` 
5. Run the script using the following prompt:  
    `streamlit run buffsaf-demo.py`
6. See [additional documentation]() for instructions on how to use the program.

**Note: Similar to Juyter Notebook, Streamlit (and this script) creates a local webserver to simplify the UI. None of your data is actually uploaded anywhere when using this script. Close the python prompt to shut the server down.**  
