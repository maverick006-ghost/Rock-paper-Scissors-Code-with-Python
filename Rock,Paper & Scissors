#Rock, Paper & scissors Game

#Ascii Art for the Game

rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

game_images = [rock, paper, scissors]

''' Objective : '''

#importing random module 
import random
#user inputs thier choice

print("Welcome to Rock, Paper & Scissors Game")
user = int(input("What do you select? : 0 - Rock, 1-Paper, 2- Scissor : "))

AI = random.randint(0,2)

#logic flow for AI to diplay the choice
if AI == 0:
    print(f"AI selected : Rock {rock}")
elif AI == 1:
    print(f"AI selected : Scissor {scissors}")
else:
    print(f"AI selected : Paper {paper}")

print(f"User selected : {game_images[user]}")   
#user logic / main game logic

if user >= 3 or user < 0:
    print("You typed an invalid number, you lose!")
elif user == 0 and AI == 2:
    print("You win!")
elif AI == 0 and user == 2:             
    print("You lose")
elif AI > user:
    print("You lose")
elif user > AI:
    print("You win!")
elif AI == user:
    print("It's a draw") 

print("Game Over")
