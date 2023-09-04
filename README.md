# python-Lab-3
Turtleworld

import turtle
# t = turtle.Turtle() 
# t.hideturtle()
# t.color('blue', 'dark blue')
# t.begin_fill()
# t.speed(20)
# for i in range(36): #För varje index i din sekvens kommer den gå 100 framåt och 100 åt vänster till den når 36.
#     t.forward(100)
#     t.left(100)
# t.end_fill()
# turtle.done() #VS will close the window when the program is done without this command. Därför måste du ge den något att göra med din turtle.

# Exercises 1-3
# import turtle
# t = turtle.Turtle()
# color= input('what color would you like:')
# t.color(color) #funktionen som ger den färg
# t.begin_fill()
# t.speed(15)
# length = int(input('give a length:'))
# for i in range(3):
#     t.forward(length)
#     t.left(120)
# t.end_fill()
# turtle.done() # för att den inte ska stänga ned

#Exercise 4-5.
# import turtle
# t = turtle.Turtle()
# t.color = ('red')
# t.speed(20)
# length = int(input('give a length:'))
# while t.distance(0,0) <= 200:
#     for i in range(100):
#         t.forward(length + i)
#         t.left(30)
#     turtle.done()

#Exercise 6. 
# import turtle
# import math
# t = turtle.Turtle()
# t.color = ('black')
# t.speed(20)
# t.fillcolor('SkyBlue')
# t.begin_fill()
# for i in range(-360,361,10): #(start, stop, increment)
#     x = i*math.pi/180 # coverts the angles in range to radians for the math.sin function. 180 is the angle of a sine curve.
#     t.goto(x*50, 200*math.sin(x)) #math.sin() returns the sine of a number. t.goto moves the turtle to an absolute position. 50 och 200 är bara för att göra det större.
# t.home() # Gå till startpunkt
# t.end_fill()
# turtle.done()

# #Exercise 7.
# import turtle
# t = turtle.Turtle()
# size = 100
# t.penup() #turtle ritar inte när den går
# t.goto(-size*1.5, -size) #Gå till nedre vänstra hörnet
# t.pendown() #Börjar dra linjer när den går

# colors = ['blue', 'white', 'red']
# sides = [size, 2*size, size, 2*size]
# for c in colors:
#     t.fillcolor(c)
#     t.begin_fill()
#     for side in sides: # går in i en loop (tre gånger för den ligger i en loop med 3 variabler i första listan) för att rita rektangel
#         t.forward(side)
#         t.left(90)
#     t.end_fill()
#     t.forward(size)
# turtle.done()
