Instructions for running the code:

Please note that this implementation was carried out on Windows 10, 
and hence the instructions are for Windows platforms.
Also note that the submission is a Jupyter notebook. I used this as opposed
to actual python files, as I felt that it best conveyed the 
analysis and inference alongside the code.

Install Anaconda:
https://conda.io/docs/user-guide/install/windows.html

Create a new enviroment with Python 3.5.4:
conda create -n myenv python=3.5.4

Activate the environment by running the following command from cmd prompt:
activate myenv


Install tensorflow 1.4.0 for Windows:
This process is quite elaborate. If using the GPU version, the CuDNN libraries need to be
placed in the right location, and the path should be in the list of environment variables.
https://www.tensorflow.org/install/install_windows


After this, the following libraries need to be installed using 
either conda or pip:
1. jupyter-1.0.0
2. scikit-learn-0.19.1 
3. keras-2.1.2
4. seaborn-0.8.1
5. pandas-0.22.0
6. matplotlib-2.1.2
7. xgboost-0.7
8. scipy-1.0.0

Go to command prompt and type "jupyter notebook" without the quotes from
the directory containing the iPython notebook. Once the browser window opens,
double click on the iPython notebook "NYC Green Cab Analysis".

Execute the code in each box for the analysis.


