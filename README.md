# 🍃 M101P: MongoDB for Developers

# Summary

`M101P: MongoDB for Developers` is part of MongoDB University series of online courses with duration of 6 weeks. Official link of the website is https://university.mongodb.com/. 
After completing this course each student should have a good understanding as to how applications are built on top of MongoDB using Python and also be prepared to take the developer associate exam and become a MongoDB Certified Professional.

- Week 1: Introduction and Overview
- Week 2: Creating, Reading and Updating Data (CRUD)
- Week 3: Schema Design
- Week 4: Performance
- Week 5: Aggregation Framework
- Week 6: Application Engineering

** For more information: https://university.mongodb.com/courses/M101/about?trk=profile_certification_title

## WEEK 1

> Homework 1.1: 

```
Install MongoDB on your computer and run it on the standard port.

Download the HW1-1 from the Download Handout link and uncompress it.

Use mongorestore to restore the dump into your running mongod. Do this by opening a terminal window (mac) or cmd window (windows) and navigating to the directory so that you are in the 
parent directory of the dump directory (if you used the default extraction method, it should be hw1/). Now type:

mongorestore dump
Note you will need to have your path setup correctly to find mongorestore.

Next, go into the Mongo shell, perform a findOne on the collection called hw1 in the database m101. That will return one document. Please provide the value corresponding to the "answer" 
key from the document returned.

Hint: if you get back a document that looks like { "_id": 1234, "answer": 2468 }, please only put in 2468 (with no spaces) for your answer.
```

Answer: 42

> Homework 1.2:

```
Get PyMongo installed on your computer. To prove its installed, run the program:

python hw1-2.py
Note that you will need to get MongoDB installed and the homework dataset imported from the previous homework before attempting this problem.

This program will print a numeric answer. Please put just the 4-digit number into the box below (no spaces).
```

Answer: 1815

> Homework 1.3:

```
We are now going to test that you have bottle installed correctly and can run a bottle-based project. Download the handout and run it as follows:

python hw1-3.py
It requires that:

bottle be installed correctly
your mongodb to be running
you have run mongorestore properly
From a different terminal window type the following from the command line: curl http://localhost:8080/hw1/50

Alternatively, you can put the url above into your web browser.

Type the two-digit answer into the box below (no spaces).
```

Answer: 53

## WEEK 2
