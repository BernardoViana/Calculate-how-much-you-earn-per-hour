# Calculate-how-much-you-earn-per-hour
An optimized and smart way to calculate how much you earn per hour using the following information  Salary + Hours per month..
""""
input monthy_salary
input hours-worked_per_month
hour-value= monthy_salary / hours_worked_per_month
print hour_value
"""

monthly_salary = input("What is your monthly salary?")
hours_worked_per_month = input("How many hours do you work per month?")
hour_value = int(monthly_salary) / int(hours_worked_per_month)
print(hour_value)
