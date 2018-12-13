# hive-queries-
Various hive table scripts and queries

patentclass: 

This has the queries to make two tables, one for a dynamic patent table partitioned by year and a class table for the class title index. Lastly it has a query to join the two tables to show information in both tables. Out of the data provided for this hive exercise I only used four columns of information out of the availible 20+ to cut down on runtime. I may add more in the future. The raw data contains over 2 million entries so it can only be handled with Hadoop software and the like. Data and class information columns came from here: 
http://www.nber.org/patents/

Information on the data is provided here:
http://www.nber.org/patents/pat63_99.txt
http://www.nber.org/patents/list_of_classes.txt

