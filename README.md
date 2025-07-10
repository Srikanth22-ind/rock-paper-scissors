# rock-paper-scissors
Today, I created a rock paper scissors game on python. I used chat gpt to fix 2 errors in my code which were capitalization mismatch and one inconsistent output 

import random

choices = ["Rock", "Paper", "Scissors"]
computer = random.choice(choices)
player = input("rock, paper or scissors?: ").capitalize()

print("computer:", computer)
print("player:", player)

if computer == player:
    print("It's a tie!")

elif computer == "Rock":
    if player == "Paper":
        print("Player wins!")
    else:
        print("Player loses!")

elif computer == "Paper":
    if player == "Scissors":
        print("Player wins!")
    else:
        print("Player loses!")

elif computer == "Scissors":
    if player == "Rock":
        print("Player wins!")
    else:
        print("Player loses!")

