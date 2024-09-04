# Python-program


# Patten 

```py
n=int(input("Enter the "))
for i in range(1,n+1):
    for j in range(1,i+1):
        print("*",end=" ")
    print("*")

```





# Divide Two Variables
## Declare two variables x and y, and assign 20 to x and 6 to y.
## Divide x by y (i.e., perform integer division x // y) and print the result.


```py
x = 20
y = 6
print(x//y)

```

# output
```
3
```





# Convert Temperature
# Declare a variable "temperature" and initialize it with a value of 25.5 (in Celsius) and print it in Celsius and Kelvin (add 273 to the temperature in Celsius).

# [Note: Print the output in exactly the same format as given below. There is single space around hyphen(-)]





```py
t= float(input("Enter temperature  : "))
print(f"Celsis -",t)
print("Kelvin -",t+273.15)

```


# output
```
temperature is : 25.5 C
temperature converted into Kelvin  298.65
Enter temperature  : 25
Celsis - 25.0
Kelvin - 298.0
```





## Area and Perimeter of Square
### Write a program to find the area and perimeter of square whose side length is 4.5. On the first line, print square's area and on the second line, its perimeter.

### Note:
### Area of a Square = side × side
### and, Perimeter = 4 x side


```py


print("Area and Perimeter of Square ")
a=eval(input("Side of Square\t"))
print("Area of a Square is  :",a*a)
print("Perimeter is  :",4*a)

```

# output
```
Area and Perimeter of Square 
Side of Square	4
Area of a Square is  : 16
Perimeter is  : 16

```






















