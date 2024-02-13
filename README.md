weight = 75
height = 1.8
P = height * height
BMI = weight / P

if BMI < 18.5:
    print("You are underweight")
if 18.5 < BMI < 24.9: 
    print("Your weight is ideal")
if BMI > 25:
    print("You are overweight")
