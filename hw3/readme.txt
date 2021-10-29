Task 2 part a: runtest_extended.sh
This script is used to gather .gcov file for each test. The program takes the input of which program to be tested. Before running the bash script, please make sure you compile the program as tcas, and name the program as it was, such as perturbed_tcas1. Please make sure the original runtest.sh is still in the same directory.

To run the program, -run- bash runtest_extended.sh -args. 
If this is for perturbed_tcas1, args is fl1; if it is for perturbed_tcas2, args is fl2; if it is for perturbed_tcas3, args is fl3. If its for perturbed_tcas0, args is orig.  

The scripts will put the output into /tcas_out/P and tcas_out/F accordingly. These folder name will (could) be the input to the part b. 



Task 2 part b: fl_Dstar.py
This script is used to compute the suspiciousness of the statements. The program outputs a table of result which required the module ‘tabulate’. Please install the module before running. -run- pip install tabulate.
 
To run the script, -run- python fl_Dstar.py
This program takes two inputs: failingDir and passingDir. Please input these two arguments as the program states. Afterwards, the results will be displayed in the table. 
