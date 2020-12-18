# udemy-python-course-notes
learning python with paid course
section 3 

string formatting
for i in range(1, 16):
    print("NO: {0:<2} squared is {1:>4} and cubed is {2:^4}.".format(i, i**2, i**3))



C:\Users\ELCOT\venv\Python3.9\Scripts\python.exe C:/Users/ELCOT/IdeaProjects/HelloWorld/sliceback.py
NO: 1  squared is    1 and cubed is  1  .
NO: 2  squared is    4 and cubed is  8  .
NO: 3  squared is    9 and cubed is  27 .
NO: 4  squared is   16 and cubed is  64 .
NO: 5  squared is   25 and cubed is 125 .
NO: 6  squared is   36 and cubed is 216 .
NO: 7  squared is   49 and cubed is 343 .
NO: 8  squared is   64 and cubed is 512 .
NO: 9  squared is   81 and cubed is 729 .
NO: 10 squared is  100 and cubed is 1000.
NO: 11 squared is  121 and cubed is 1331.
NO: 12 squared is  144 and cubed is 1728.
NO: 13 squared is  169 and cubed is 2197.
NO: 14 squared is  196 and cubed is 2744.
NO: 15 squared is  225 and cubed is 3375.

Process finished with exit code 0

in string formating replacement
:< left align 
:> right align
:^ centered allaign

In between string {} uses to store 0, 1, 2.. and we use .format operater to replace the numbers 0, 1, 2 to anything we want

print("Pi is aproximately {0:12}".format(22/7))  #general formate, default to print 15 digit decimal values
print("Pi is aproximately {0:12f}".format(22/7))  #when we sqecify the floating point, we get default 6 decimals
print("Pi is aproximately {0:12.50f}".format(22/7))
print("Pi is aproximately {0:52.50f}".format(22/7))
print("Pi is aproximately {0:62.50f}".format(22/7))
print("Pi is aproximately {0:<72.50f}".format(22/7))
print("Pi is aproximately {0:<72.54f}".format(22/7))

C:\Users\ELCOT\venv\Python3.9\Scripts\python.exe C:/Users/ELCOT/IdeaProjects/HelloWorld/sliceback.py
Pi is aproximately 3.142857142857143
Pi is aproximately     3.142857
Pi is aproximately 3.14285714285714279370154144999105483293533325195312
Pi is aproximately 3.14285714285714279370154144999105483293533325195312
Pi is aproximately           3.14285714285714279370154144999105483293533325195312
Pi is aproximately 3.14285714285714279370154144999105483293533325195312                    
Pi is aproximately 3.142857142857142793701541449991054832935333251953125000                

Process finished with exit code 0






























