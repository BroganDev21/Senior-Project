Attempt to create a language model that will be able to determine origin of written text based off of word frequency and count. 
Senior Project - University of Mississippi
Sponsored by Dr. Hong Xiao

Senior Project
---------------------------------------------------------------------------------


SETUP:
--------------------------------------------------------------------------------
- Ensure all files have been downloaded either from box, turing, or github (insert links here)
- If following my process, download and install the anaconda framework, as well as anaconda navigator
- Open SeniorProject.ipynb and in a new cell pip install and download any necessary dependencies for the environment (See User Manual)
- before running cells, ensure all file paths are accurately changed to match your system paths where the files are stored. My paths look like(C:\Users\Colin\OneDrive\Desktop\Senior Project Code\Senior-Project\)


EXECUTION
--------------------------------------------------------------------------------
- Execute all cells in order! 
	* due to how I initially arranged my import statements and jupyters kernel system, if this project is left running for an extended period of time or first opened. Cells should all be ran in sequential order to properly initialize any functions objects, or variables.
- Simply click the run this cell or restart the kernel and run all cells button in jupyters tool-bar 
- To use the model, run the Feature Cell then the Test Cell. 
	* WARNING: Running the Random Forest Cell will retrain the model, potentially producing a less accurate model for tests. I have been troubleshooting this with
	Dr. Hong but did not have time to properly determine a fix. Potentially from overfitting due to class imbalance and not using a random_state to determine seed. 
- When executing test cell, ensure file path for the .joblib model is correct, as well as the folder in which the test essays are stored.
- To add a new essay to be classified, simply drop a .docx file into the test_essay folder then run the test cell, it will then output the models prediction


