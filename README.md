# python-student marksheet system
name = input("Enter student Name:")
rollnumber = input("Enter student Roll number:")
marks_input = input("Enter student marks (seperated by space):")
marks = list(map(int, marks_input.split()))
total = sum(marks)
average = total / len(marks)
if average>90:
  Grade= "A"
elif average>75:
  Grade="B"
elif average>50:
  Grade= "C"
else:
  Grade="Fail"

print("student marksheet system")
print("Name:",name)
print("Roll number:", rollnumber)
print("Marks:", marks)
print("Total marks:", total)
print("Average marks:", average)
print("Grade", Grade)
