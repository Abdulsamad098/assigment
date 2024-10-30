# assigment
#Q1
base =  10
height = 20
area = 0.5 * base * height
print(f"The area of the triangle is: {area}")


#Q2

def square_area(side):
    return side * side

side = float(input("Enter the length of a side of the square: "))
area = square_area(side)
print(f"The area of the square is: {area}")


#Q3

import math

def circle_area(radius):
    return math.pi * radius * radius


radius = float(input("Enter the radius of the circle: "))
area = circle_area(radius)
print(f"The area of the circle is: {area}")


#Q4

def rectangle_area(length, width):
    return length * width

    
length = float(input("Enter the length of the rectangle: "))
width = float(input("Enter the width of the rectangle: "))

area = rectangle_area(length, width)
print(f"The area of the rectangle is: {area}")
