-------------------------------------------
		GROUP 9 : MAHABHARATATA IR

	   SUBJECT: INFORMATION RETRIEVAL
		
		   SUBJECT CODE : CS657A
-------------------------------------------


Dependencies:

- csv	:  to manage data
- pandas : for dataset handling
- numpy : support for calculations
- math :  for mathematical operations
- nltk : for tokenization, stemming and using stopwords
- collections : for python dictionary
- unidecode : to convert into ASCII characters
- pickle : to save data objects
- re : for regular expression
- math : for mathematical operations
- string : for string manipulation
-pyserini:for performing passage retrieval task

We have automated those installs but if any other library is missing install them by writing pip install library_name in the command line.
(for any query i am assuming there will be atleast one word which is present in the corpus otherwise my system will return no files)

The system requires GPU to load encoders. We used Google colab for the same. The instructions below are for executing these files in Google Colab. 


How to run APPROACH 1:
	- Upload CS657A:Approach_1.ipynb to colab.
	- Upload context_ques_ans.csv and Mahabharta_dataset.txt to the colab directory
	- Run the file
How to run APPROACH 2and3:
	- Upload CS657A:Approach_2_3.ipynb to colab.
	- To run Approach 2, set model_flag to True and for Approach 3, set it to False. 
	- Upload context_ques_ans.csv and Mahabharta_dataset.txt to the colab directory
	- Run the file
How to run APPROACH 4:
	- Upload the folder cs657A_project on google drive
	- The script already contains command to mount the drive,make sure the folder uploaded must have same name as   
	   "CS657A_project"
	- Run the "CS657A:Approach_4.ipynb"

Link to Dataset : https://drive.google.com/drive/folders/1e04Rk994b7bNESLQASAlEZpTSjL7hK12?usp=sharing




