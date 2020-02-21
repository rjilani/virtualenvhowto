# How to create virtual environment Python 3

1. Make a directory and cd to the new directory

	mdkir virtualenvtest
	cd virtualenvtest
	
2. From the root directory run the follwoing command, this will create the new Python env on your machine with defualt core 
   Python environment

	python -m venv .
	
3. run Scripts/activate.bat from the root folder and your promt will change to the new virtual env

4. Run pip list to see you have a clean installation of python environment

5. If you want to deactivate the virtual env and go back to the global python isntalled environment, you can run 
   the following command
   
   Scripts/deactivate.bat
