# Setup for Introduction to Quantum Computing Workshop

### 1)	Make an account with IBM Q. Here, you can create circuits on the online GUI. You will also use the online interface to grab the token associated with your IBM Q account so that you can run experiments from your computer via Qiskit.

	•	https://www.ibm.com/quantum-computing/


### 2)	Qiskit, the IBM Q SDK (https://qiskit.org ), has many dependencies. The easiest way to make sure you have everything you need is to download and install Anaconda on your machine. Use Python 3.7. There are distributions for Windows, MacOS, and Linux.

	•	https://www.anaconda.com/distribution/

### 3)	If you already have Python set up on your machine and would like to keep Qiskit separate from other applications (helpful if you have particular versions of packages for ML applications, for example), you can set up an environment just for your quantum work. 

	•	‘conda env list’ -> list your environments (if you just installed anaconda, you will only see ‘base’)

	•	‘conda create --name my-quantum-env --clone base’ -> clone your base and create a new quantum environment 

	•	‘conda activate my-quantum-env’ -> switch to your new environment

### 4)	Once your python environment has been established. Install Qiskit!

	•	‘pip install qiskit’

	•	More information about installation can be found here: https://qiskit.org/documentation/install.html 

### 5)	Download the workshop Jupyter notebook ‘workshop-notebook’

	•	https://github.com/knsmith/quantum-workshop-materials 

6)	Open a terminal and navigate to the directory where the workshop Jupyter notebook is saved. Run Jupyter notebook and open the notebook in your browser.

•	‘jupyter notebook’ -> run in terminal to open up notebook environment in a web browser

7)	Find the variable ‘token’ in the notebook. Exchange it with your IBM Q account token found under the ‘my account’ page. With this final piece, you should be ready to run the examples!

