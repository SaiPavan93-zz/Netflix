1) There are 4 .py files 
		alsm.py : ALS algorithm
		svd : SVD algorithm
		myalg : Mean and standard deviation
		bigdata : Preprocessing files
		
2) Combined_data_1_1 to Combined_data_4_2 are the input files for preprocessing.

3)output1 and output2 are the files generated from output file as the file is very large and memory error
  occurs on loading it.
  
4)The preprocessing must be done in pySpark (Recommend use of Amazon AWS)
    1)m4.x large clusters should be used and 10 nodes must be taken.
	2)output file is output of preprocessed file.
	
5)The other 3 .py files must be run in python 3.4 and the required packages must be installed inorder to run the files.

NOTE : All the data files must be kept in the same path where the code files reside.Kidly,Recommend you to place all the files in the same directory structure.The Algorithms has been implemened in Python 3.5.So, any interpreter below 3.5 version may not work properly
as the syntaxes will be different for different interpreters.