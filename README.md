import random
choices=["rock" , "paper" , "scissor"]

computer= random.choice(choices)

player=input("Choose rock,paper,scissor:")
if player == computer:
    print("It's a tie!")
    
elif (player == "rock" and computer == "scissors") or (player == "paper" and computer == "rock") or (player == "scissors" and computer == "paper"):
    print("You win!")
else:
    print("Computer wins!")
