# Python_BMI_Calculator
This is a small project. Creating a BMI calculator in Python using Jupyter Notebook.

<h1> BMI Calculator </h1>

<p>
  #Reference

Under 18.5	Underweight	Minimal
18.5 - 24.9	Normal Weight	Minimal
25 - 29.9	Overweight	Increased
30 - 34.9	Obese	High
35 - 39.9	Severely Obese	Very High
40 and over	Morbidly Obese	Extremely High
</p>

<p>
  name = input("Enter your name: ")

weight = int(input("Enter your weight in pounds: "))

height = int(input("Enter your weight in inches: "))


BMI = (weight * 703) / (height * height)

print(BMI)

if BMI>0:   
    if(BMI<18.5):
        print(name +", You are underweight.")
    elif(BMI<24.9):
        print(name +", You are normal weight.")
    elif(BMI<29.9):
        print(name +", You are overweight.")
    elif(BMI<34.9):
        print(name +", You are obese.")
    elif(BMI<34.9):
        print(name +", You are severely obese.")
    
else: print("Enter valid input")
                    
  </p>
