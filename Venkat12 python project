#stone, paper,scissor game.
import random

#cp input
def computerchoice():
    computerchoice=["stone","paper","scissor"]
    getcomputerChoice=random.choice(computerchoice)
    print(f"computerchoice={getcomputerChoice}")
    return getcomputerChoice
#user input
def userChoice():
    userChoice=input("enter a item").lower()
    return userChoice
#gamerule
def gameRule(userplay,computerplay):
    #draw
    if userplay==computerplay:
        print("Match Draw")
    #user win
    elif userplay=="stone" and computerplay=="scissor":
        print("User Win")
    elif userplay=="paper" and computerplay=="stone":
        print("User Win")
    elif userplay=="scissor" and computerplay=="paper":
        print("User Win")
    # coputer win
    elif userplay=="scissor" and computerplay=="stone":
        print("Computer Win")
    elif userplay=="paper" and computerplay=="scissor":
        print("Computer Win")
    elif userplay=="stone" and computerplay=="paper":
         print("Computer Win")
gameRule(userplay=userChoice(),computerplay=computerchoice())
