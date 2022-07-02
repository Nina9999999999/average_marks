# average_marks
###############################
def marksis():
    marks=[55,64,75,80,65]
    marks_sum=sum(marks)
    marks_length=len(marks)
    marks_average=marks_sum/marks_length
    print("your average mark is", marks_average)
    if marks_average>= 80:
        print("wow, you get A")
    elif (marks_average>=60) and (marks_average<80):
        print("you get B")
    elif (marks_average>=50) and (marks_average<60):
        print("you get C")
    elif (marks_average<50):
        print("you get F")
  
marksis()
###############################

# function for the average of marks
def marksis():
    marks=[55,64,75,80,65]
    marks_sum=sum(marks)
    marks_length=len(marks)
    marks_average=marks_sum/marks_length
    return marks_average

marks_average=  marksis()
### function for determine your grade
def your_grade(marks_average):    
    if marks_average>= 80:
        grade='A'
    elif (marks_average>=60) and (marks_average<80):
        grade='B'
    elif (marks_average>=50) and (marks_average<60):
        grade='C'
    elif (marks_average<50):
        grade='D'
    return grade

print(marks_average)
grade=your_grade(marks_average)
print( grade)
