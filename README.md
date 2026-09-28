# student_persentage
THIS IS MY FIRST PROJECT. THIS PROJECT IS FOR ONCE WHO DONT KNOW TO CALCULATE PERSENTAGE OR WORK WITH LARGE DATA TO FIND THE PERSENTAGE FOR MANY STUDENTS. BASICLY THIS PROJECT IS FOR SCHOOL MEMBERS WHO ARE SUPPOSED TO PREPARE REPORTCARD FOR THEIR STUDENTS.
<br>
AUTHOR-SHIVANSH PRAJAPATI.
<br>
print("welcome to this program(made by shivansh prajapati)")
print("This program will hep you to find out your persentage for scool exam/test ")
print("But be awair that this program is for DPS KALYANPUR school")

name=input("Entere the name of your child_")
age=int(input("ENTERE THE AGE OF THE STUDENT_"))
CLASS=int(input("Entere the class  of your child_"))
if CLASS<= 6:
    print("This program is perfect for you") 
else:   
    print("sorry this program is not for you ")
student=int(input("Entere the number of student in your class_"))

print("Give the data of PA1 below asked")


hindi=int(input("Entere the marks of HINDI of your student"))
english=int(input("Entere the marks of ENGLISH of your student"))
maths=int(input("Entere the marks of MATHS of your student"))
sst=int(input("Entere the marks of SST of your student"))
ai=int(input("Entere the marks of AI of your student"))
science=int(input("Entere the marks of SCIENCE of your student"))


total=(hindi+english+maths+sst+ai+science)

print("total marks=",total)



persentage=total/240*100
print("persentage=",persentage)






print("Give the data of PA2/HALFYEARLYS below asked")


hindi=int(input("Entere the marks of HINDI of your student"))
english=int(input("Entere the marks of ENGLISH of your student"))
maths=int(input("Entere the marks of MATHS of your student"))
sst=int(input("Entere the marks of SST of your student"))
ai=int(input("Entere the marks of AI of your student"))
science=int(input("Entere the marks of SCIENCE of your student"))

total=(hindi+english+maths+sst+ai+science)

print("total marks=",total)



persentage=total/480*100
print("persentage=",persentage)




print("Give the data of PA3 below asked")


hindi=int(input("Entere the marks of HINDI of your student"))
english=int(input("Entere the marks of ENGLISH of your student"))
maths=int(input("Entere the marks of MATHS of your student"))
sst=int(input("Entere the marks of SST of your student"))
ai=int(input("Entere the marks of AI of your student"))
science=int(input("Entere the marks of SCIENCE of your student"))

total=(hindi+english+maths+sst+ai+science)


print("total marks=",total)





persentage=total/240*100
print("persentage=",persentage)



print("Give the data of FINALs below asked")


hindi=int(input("Entere the marks of HINDI of your student"))
english=int(input("Entere the marks of ENGLISH of your student"))
maths=int(input("Entere the marks of MATHS of your student"))
sst=int(input("Entere the marks of SST of your student"))
ai=int(input("Entere the marks of AI of your student"))
science=int(input("Entere the marks of SCIENCE of your student"))

total=(hindi+english+maths+sst+ai+science)

print("total marks=",total)



persentage=total/480*100
print("persentage=",persentage)



marks1=int(input("Entere  total marks for PA-1(out of 240) "))
marks2=int(input("Entere  total marks for PA-2(out of 480) "))
marks3=int(input("Entere  total marks for PA-3 (out of 240)"))
marks4=int(input("Entere  total marks for FINAL (out of 480)"))


avg_marks1=(marks1-marks2)
avg_marks2=(marks3-marks4)
avg_marks=(avg_marks1-avg_marks2)

print(avg_marks)




print("___________STUDENT REPORT__________")
print("Name of the student=",name)
print("Class of the student=",CLASS)
print("total marks =",total)
print("persentage=",persentage)


if persentage >=90:
    print("conguratulations you are scholar")
else:
    print("Do hard work next time")

print("___teacher remark__")
if persentage>=95:
    print("your child is very good in studys child ")
elif persentage>=90:
    print("your child is good in studys")
elif persentage>=80:
    print("your child need a little more effortt")
else:
    print("your child need hard work")
