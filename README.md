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



## How to run BuffSAF-Demo

### HTML version - UNSTABLE

The HTML version of BuffSAF Demo is intended for use in justifications of getting a Python environment installed. With care, I've gotten it stable up to batches of 375 mb. 
>Warning: Please ensure you only click on the "Compile" button once, as it will hang with no visibile indication that it is processing the file in the html version.

This version uses [pyodide](https://github.com/pyodide/pyodide) and [stlite](https://github.com/whitphx/stlite) to run fully in a client-side browser. 

To run this version: 

1. Click on [BuffSAF-Demo.html](https://github.com/brucejwardlow/buffsaf-demo/blob/main/buffsaf-demo.html)
2. Click on the download icon in the top right corner.
3. Double click the .html file to run the program.
4. See [additional documentation]() for instructions on how to use the program.

### Python Version

This is the fully functional, stable version currently in production use at West Texas A&M University. 

There is a version with more features available at [BuffSAF](https://github.com/brucejwardlow/BuffSAF), however that version is still in development and has a much more complex installation process and less documentation. 


 
To run this version: 

1. Click on [BuffSAF-Demo.py](https://github.com/brucejwardlow/buffsaf-demo/blob/main/buffsaf-demo.py)
2. Click on the download icon in the top right corner.
3. Install a python environment. (I recommend [Anaconda](https://www.anaconda.com/))
4. Open python prompt.
5. Navigate to the folder containing the .py file.    
>Warning: This version of the script will delete any folder titled "temporary" in the same location as the .py file. Putting the file in its own folder is recommended.
6. Install pandas using the following prompt:  
    `pip install pandas`
7. Install streamlit using the following prompt:      
    `pip install streamlit` 
8. Run the script using the following prompt:  
    `streamlit run buffsaf-demo.py`
9. See [additional documentation]() for instructions on how to use the program.

>Note: Similar to Jupyter Notebook, Streamlit (and this script) creates a local webserver to simplify the UI. None of your data is actually uploaded anywhere when using this script. Close the python prompt to shut the server down. 
