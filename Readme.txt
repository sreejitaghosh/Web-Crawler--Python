Below are the steps to run this Project.

1) Open command prompt and go to directory containing this folder using command cd "Directory Path"
	Eg.: cd D:/IRWS

2) Enter command "python MainScript.py"

3) Program will ask for user input to give path of offline saved web pages without file name and file extension. Please give appropriate input.
	Eg.: C:/Users/Srej/Downloads/IRWS/Corpus/
	Note : Please do not forget to put "/" at the end else program may not work and throw error of file not found at the given path.

4) Program will next ask for user input to give file name and file extention. Please give appropriate input.
	Eg.: mainpage.html

5) Program will perform all calculations till Page Length/Weight. It will display Tokens, Tokens after stopwords removed and stemmed, TF, IDF, TF-IDF and Page Length.
   Program will now ask for user query 1. Give appropriate input.
	Eg.: This is sample query 1.
   Program will now ask for user query 2. Give appropriate input.
	Eg.: Query 2 given here.

6) Program will display page rank as per calculations based on user query 1 and user query 2 with each document.
   Program will now ask for input to assign weightage of 100 to given webpage name from displayed webpages on screen. Please give appropriate input here.
	Eg.: doc6.html

7) Program will now calculate Page rank values in 20 iterations and will display assigned page rank with page rank values. Page with top ranks will be displayed first with it's page rank values followed by least important page.
