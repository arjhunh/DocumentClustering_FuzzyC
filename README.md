README
-------------------------------------
There will be 2 files, one for the Reuters data clustering and the other for the Ohsumed data clustering.

In order to run the code you will need the following installed:

	1. Python
	2. PySpark
	3. IpythonNotebook

You will also need the following packages/libraries installed in python:

	1.	Pandas (data handling)
	2.	NumPy (data handling)
	3.  NLTK (for stemming)
	4.	Scikit-fuzzy (for off the shelf fuzzy C Means algorithm)
	5.	Scikit-learn (for PCA)
	6.	Matplotlib (for plots)
	7.	Scipy (K means clustering algorithm)

You can download the dataset we used for our project here:
	1. Reuters - https://drive.google.com/open?id=0B6CPjKbb179Sd0NrYnhISGNtYTQ
	2. Ohsumed - https://drive.google.com/open?id=0B6CPjKbb179Sc3Jjb2h6SWc0T1E
	3. Stopwords - https://drive.google.com/open?id=0B6CPjKbb179SQXRXdlRwdkF4U0k
	
NOTE: We suggest you run the program on a cluster and not on your local machine as it might take very long for computations if run locally.

INSTRUCTIONS FOR RUNNING THE CODE:

1. The first cell of code is for integration of Amazon S3 in Databricks (the platform we used for writing and running the program). This can be ignored.
2. The second cell of code is where the data is imported. Depending on how you are going to access your data (either from AWS or locally), add the directory
   of the file corresponding to the program you are running (ohsumed or reuters). If you're running the reuters program, add the path to the .txt file. If you're running
   the Ohsumed program, add the path to the folder containing all the files (extracted from the .zip file).
3. In the third cell of code, add the path to the english stopwords text file (mentioned above).
4. All the other cells can be run now (provided all the libraries and packages mentioned above are installed). You will be able to see the plots then and there as you run the code.
5. The last cell of code is where all the results are exported out for analysis. Change the directories for those as required to view the results files.

These instructions should suffice for running the programs successfully. In case of any questions, contact:
	Arjhun Hariharan (hariharan.36@osu.edu)
	Varun Mohan Kumar (mohankumar.7@osu.edu)