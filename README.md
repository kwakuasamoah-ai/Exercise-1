# Exercise-1
Temperature 
# Ask the user for temperature in Celsius
celsius = float(input("Enter temperature in Celsius: "))

# Convert to Fahrenheit
fahrenheit = (celsius * 1.8) + 32

# Output the result
print("Temperature in Fahrenheit:", fahrenheit)

# Bonus conditions
if celsius < 0:
    print("Freezing!")
elif celsius > 30:
    print("Hot!")
