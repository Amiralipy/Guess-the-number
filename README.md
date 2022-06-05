# Guess-the-number
#Hello dear friend I tried to be able to challenge my family! You too can challenge your family  I hope it is an interesting game to challenge
from sys import *
from random import *
print("Welcom to my chalange game:)")

print(" ")
print("You shoud use (Yes,no)")
soal =input("Are you ready for game?? :")
Yes="Yes"
yes="yes"
No="No"
no="no"
if soal == (no):
    exit()
elif soal == (No):
    exit()
else :
    print("Lets start")
    print("   ")
    
print()
print("              * * * * * * * * * * * * * * *")
print("              *       bro a number        *")
print("              *          between          *")
print("              *         10 and 99         *")
print("              *                           *")
print("              *        (You have 6)       *")#<----You can increase 6
print("              *           chances         *")
print("              * designer:AmirAli farahani *")#<-----you can edit this
print("              * name game:Guess the number *")
print("              *-----------(A.F)-----------*")

number = randint(10,99)
for i in range(6,0,-1):
    hads= int(input("Enter a guess pls:"))
    if hads == number :
        print("WooW you win 😃")
        exit()
    elif hads < number :
        print("my numbr is bigger than your number!🧐")
    else:
        print("my number is smaller than your number!🧐")


print(" ")
print("               * * * * * * * * * * * * * *")
print("               *         You lost        *")
print("               *  My number is",number, "*")
print("               * * * * * * * * * * * * * *")

#python file
