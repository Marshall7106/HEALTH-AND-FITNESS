# Hardcoded example for BMI and BMR calculations
weight = 70  # kg
height = 1.75  # meters
age = 25  # years
gender = "male"  # or "female"

# BMI Calculation
bmi = weight / (height ** 2)

# BMR Calculation
if gender == "male":
    bmr = 10 * weight + 6.25 * (height * 100) - 5 * age + 5
else:
    bmr = 10 * weight + 6.25 * (height * 100) - 5 * age - 161

print(f"BMI: {bmi:.2f}")
print(f"BMR: {bmr:.2f} kcal/day")
