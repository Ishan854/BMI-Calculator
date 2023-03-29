# BMI-Calculator
Here's the updated code with a simple condition to classify the BMI result as either underweight, normal, overweight or obese:

name = input("Enter Your Name ")

weight = int(input("Enter your weight in pounds."))

height = int(input("Enter your height in inches."))


bmi = weight * 703/ (height**2)

print(bmi)

if bmi>0:


  if bmi<18.5:
  
    print(name +", Your are under weight")
    
  elif bmi<24.9:
  
    print(name +", Your are normal weight")
    
  elif bmi<30:
  
    print(name +", Your are over weight")   
    
  elif bmi<34.9:
  
    print(name +", Your are obese")
    
  elif bmi<39.9:
  
    print(name +", Your are severely weight")
    
  else:
  
    print("you are morbidly obese")  
    
else:

    print("Enter Valid Input")  
    
    
we first calculate the BMI as before, and then use an if-elif-else block to classify the result into four categories:

# Underweight for BMI values less than 18.5
# Normal weight for BMI values between 18.5 and 24.9
# Overweight for BMI values between 30 and 34.9
# Obese for BMI values 39.9 and above
We then print out a message to the user indicating which category their BMI falls under. Note that this is just a basic classification and should not be used as a substitute for professional medical advice.





   
