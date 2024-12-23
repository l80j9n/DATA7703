java cS2 - 2024 DATA7703 – Machine Learning for Data Scientists
Assignment 1
Decision Trees
Due date: Friday Aug 16 3pm
1. Training a Decision Tree
- First complete Q1 using the scikit-learn (sklearn) library (40%)
- Next complete Q1 without using any ML libraries, (ie. implement a decision tree
algorithm from scratch) (30%)
Write a program in Python to implement the ID3 decision tree algorithm. You should read in
a tab delimited dataset, and output to the screen the relevant results in some readable format.
 Name your program decisiontreeassignment.py
 Basic math and file reading functions from libraries such as numpy or pandas etc. are
allowed.
There are two sample datasets available from the course blackboard page you can use
 tennis.txt - Predict whether or not your tennis partner will join you to play tennis
based on weather.
 titanic2.txt - Predict the survival status of individual passengers on the Titanic based
on their passenger class, age and gender.
For the dataset files
 The first line of the file will contain the name of the fields.
 The last column is the classification attribute, and will always contain the
values yes or no.
 All files are tab delimited.
When you run your program, it should take a command-line parameter that contains the name
of the file containing the training data. For example:
python decision代 写DATA7703、Python
代做程序编程语言treeassignment.py tennis.txt
And it should output the training set accuracy in some readable form. You do not need to
print or display the resulting tree (unless you want to).
2. Max Tree Depth (15%)
- First complete Q2 using scikit-learn (sklearn) library (10%)
- Next complete Q2 without using any ML libraries (5%)
Add to your implementation so that you can limit the maximin tree depth. It should now take
an additional command-line parameter that sets the maximum tree depth. For example:
python decisiontreeassignment.py tennis.txt 5
3. Test Set (15%)
- First complete Q3 using scikit-learn (sklearn) library (10%)
- Next complete Q3 without using any ML libraries (5%)
Add to your implementation so that you can also pass a file containing data not in the training
data. It should now output the training set accuracy as well as the testing set accuracy in some
readable form.
The command-line call should now have a third parameter containing the name of the file
containing the testing data. For example:
python decisiontreeassignment.py tennis_trainingset.txt 5 tennis_testset.txt
You can create training and testing sets by (randomly) splitting the available data
appropriately.
Submission
Assignments to be completed individually and submitted through blackboard.
Due date
Friday Aug 16 3pm.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
