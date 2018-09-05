# CS-AS


EXERCISE 1
A = "All"
B = "work"
C = "no"
D = "play"
E = "makes"
F = "Jack"
G = "a"
H = "dull"
I = "boy"
print(A,B,C,D,E,F,G,H,I)

EXCERCISE 2
print(6*(1-2))

EXERCISE 3
#This is a comment
A = "All"
B = "work"
C = "no"
D = "play"
E = "makes"
F = "Jack"
G = "a"
H = "dull"
I = "boy"
print(A,B,C,D,E,F,G,H,I)

EXERCISE 4
bruce = 6
print(bruce + 4)

EXERCISE 5
P = 10000
r = 0.08
n = 12
t = int(input("How many years?"))
A = P*(1+(r/n))**(n*t)
print(A)

EXERCISE 6
print(5%2)
print(9%5)
print(15%12)
print(12%15)
print(6%6)
print(0%7)

EXERCISE 7

time = 14
timepassed = int(input("howmuchtime?"))
print(time+(timepassed%24))

EXERCISE 8
time = int(input("What time is it?"))
timepassed = int(input("How much time has passed?"))
if timepassed > 24 :
    print(time + (timepassed % 24))


if timepassed< 24 :
    print(time + timepassed)
    if (time + (timepassed % 24)) > 24 :
        print(((time + (timepassed % 24)) - 24))
        
CHAPTER 3

EXERCISE 1 

for f in range (1000) :
    f = "We like Python's Turtles"
    print(f)

EXERCISE 2

for f in  ("January","February","March","April","May","June","July","August", "September","October","November", "December"):
   invite = "One of the months opf the year are " + f + " "
   print(invite)
   
EXERCISE 3

import turtle

wn = turtle.Screen()

tess = turtle.Turtle()

tess.left(3645)

wn.mainloop()

EXERCISE 4 



EXERCISE 11

import turtle
wn = turtle.Screen()
wn.bgcolor("lightgreen")
wn.title("Hello, Tess!")

tess = turtle.Turtle()
tess.color("red")
tess.shape("turtle")
tess.pensize(2.5)

for i in range (5):
    tess.forward(500)
    tess.left(144)

wn.mainloop()



