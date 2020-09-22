# Search Engine
## Created by: Ibrahim Idkedek, Montaser Jafrah

### In this project there is two classes :
####	1)IndexWriter.py:
		in this class we have two main functions :
			a)write(inputFile, dir):inputFile is the path to the file containing the review data,
			dir is the directory in which all index files will be created,if the directory does not exist, it will be created
			this functions reads the data from inputfile and creates 4 files that containing the data that we need.	
	
			b)removeIndex(dir):removes the dirictory that was created by the function above.
			
		Run/compile:
			calling the method Slowwrite with input (file_name,directory_name)

####	2)IndexReader.py:
		this class reads the data from the files that we created in the class above and it returns specific data according to
		the function that was called(all function have comments about what they are doing)

