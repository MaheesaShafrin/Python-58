# Python-58
 Python program to find the circumference and area of a circle with a given radius
import math

r = float(input("Input the radius of the circle: "))

circumference = 2 * math.pi * r
area = math.pi * r ** 2

print("The circumference of the circle is: {:.2f}".format(circumference))
print("The area of the circle is: {:.2f}".format(area))

Output:
Input the radius of the circle: 5
The circumference of the circle is: 31.42
The area of the circle is: 78.54
