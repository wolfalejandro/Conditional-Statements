'''
For this assignment you should read the task, then below the task do what it asks you to do.
'''

'''
#1) Create a Variable called grade and set it to an integer. Make an if statement that checks if the grade is a passing grade. grade must be above 65 to pass. print out "student is passing"
'''
Grade=80
if(Grade >= 65):
    print ("Student is passing")
'''
#2) Now make an if, else statement that checks if the student is passing but also print "student is failing", if the grade is less than 65
'''
if(Grade >= 65):
        print("Student is passing")
elif(Grade <= 65):
    print("Student is failing")
'''
#3)Create a variable called age. Make and if, else statement that checks if the age entered is old enough to vote. Remember the voting age is 18
'''
Age=18
if(Age>= 18):
    print("Able to vote")  
elif(Age<= 18):
    print("Unable to vote")
'''
#4)Create a variable called weight. Make an if statement that checks the unit of the weight. If the weight is in kilograms, convert it to pounds 
'''
Weight="kilograms"
if(Weight == "kilograms"):
    print("Convert to pounds")
'''
#5)Now modify the previous program to also convert from pounds to kilograms
'''
Weight="pounds"
if(Weight == "pounds"):
    print("Convert to kilograms")   