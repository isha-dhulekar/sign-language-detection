# sign-language-detection
sign language dectection project using CNN algorithm 
### Prerequisites and Installing
Follow the below steps to set up the virtual environment locally

1. Pip is installed by default on many newer python builds, to check if it is installed, type
	```
	pip help
	```

2. Install virtualenv using
	```
	pip install virtualenv
	```

3. Inside the project directory run the following command
	```
	python -m venv myenv
	```

4. To activate the created environment :
	
	#### For Windows :
	```
	myenv\Scripts\activate
	```

	#### For Mac/Linux:
	```
	source myenv/bin/activate
	```

5. Now install the packages from the 'requirements.txt' file
	```
	pip install -r requirements.txt
	```

**Note** - If you are using Mac/Linux then use pip3 instead of pip and python3 instead of python.

After this, you are ready to run the code in your machine!

### Output
We have implemented the live classification of sign language through our model using [OpenCV](app.py/).
cmd -> cd file name -> openCV -> app.py
