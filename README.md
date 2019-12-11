#SET-COMMAND-INTERPRETER-v2.0
*SetCommandInterpreter* is a shell/terminal that supports set operations.
This application allows you to work with sets.
##*NOTE: All sets work with integers only*


#UPDATES
1. Bugs in SetCommandInterpreter-v1.0 fixed
2. Enhanced security of data
3. Updated exception handling mechanism
4. Added feature of command history


#SUPPORTED COMMANDS
The following commands are supported by the application:
1) To add integers to pre-existing set, we use
	add <set_name> <integer1> <integer2> <integer3> ...
	e.g. 
	/home/shailly:~$ add set1 10 20 30 40 50 60 70 80 90 100
2) To clear the shell/terminal, we use
    clear
	e.g. 
	/home/shailly:~$ clear
3) To clear a pre-existing set (delete its all elements), we use
	clear <set1_name> <set2_name> <set3_name> ...
	e.g. 
	/home/shailly:~$ clear set1 set2
4) Test for existence of integer in a pre-existing set
	contains <set_name> <integer1> <integer2> <integer3> ...
	e.g. 
	/home/shailly:~$ contains set1 10 20 30 40 50 60 70 80 90 100
5) To save the changes to database, we use commit command
	commit
	e.g. 
	/home/shailly:~$ commit
	Note that your work isn't saved unless you commit it!!
6) To delete a pre-existing set, we use
	del <set_name>
	e.g. 
	/home/shailly:~$ del set1
7) To delete specific elements in a pre-existing set, we use
	del <set_name> <integer1> <integer2> <integer3> ...
	e.g. 
	/home/shailly:~$ del set1 10 20 30 40 50 60 70 80 90 100
8) To delete all sets, we use
	delall
	e.g. 
	/home/shailly:~$ delall
9) To exit from terminal, we use
	exit
	e.g. 
	/home/shailly:~$ exit
10) To get the details of command, we use
	help
	e.g. 
	/home/shailly:~$ exit
11) To get the insersection of sets, we use
	int <result_set> <set1_name> <set2_name> ...
	e.g. 
	/home/shailly:~$ int set4 set1 set2 set3
	set4 = int(set1,set2,set3)
12) To get a list of all sets, we use
	ls
	e.g. 
	/home/shailly:~$ ls
13) To make set(s), we use
	mkset <set1_name> <set2_name> <set3_name> ...
	e.g. 
	/home/shailly:~$ mkset set1 set2 set3 set4
14) To display the content of pre-existing set(s), we use
	print <set1_name> <set2_name> <set3_name> ...
	e.g. 
	/home/shailly:~$ print set1 set2 set3
15) To rename a pre-existing set, we use
	rnm <old_set_name> <new_set_name>
	e.g. 
	/home/shailly:~$ rnm set1 new_set1
16) To get the cardinality of pre-existing set(s), we use
	size <set1_name> <set2_name> <set3_name> ...
	/home/shailly:~$ size set1 set2 set3
17) To get the union of sets, we use
	union <result_set> <set1_name> <set2_name> ...
	/home/shailly:~$ union set3 set1 set2
	set3 = union(set1, set2)
-

#REQUIREMENTS
Make sure you have installed OpenJDK8 Java Runtime Environment



#INSTALLATION
You need not to install anything to try this application.
You are given a jar file(SetCommandInterpreter.jar), you just need to
double click on it and the application will start for you.



#RUNNING ISSUE
Depending of the platform(OS) you are using it may be possible that
your OS may not give execution permission to the given jar file.
If so then there are two ways to fix this issue i.e.
1) Change the permission of the jar file and mark it is as executable
2) Use terminal and execute the following command:

##a) First of all navigate to the directory wherever SetCommandInterpreter.jar is located.
##b) Execute java -jar SetCommandInterpreter.jar




#COPYRIGHT
Copyright© 2019
All rights reserved
Shailly Jain (Meerut Institute of Engineering and Technology) 
(shaillyjain1512@gmail.com)
