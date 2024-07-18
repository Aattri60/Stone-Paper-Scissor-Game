Import random
print("Choose one from Stone, Paper, Scissor")
print("let's get started")
Game = input(" Stone Paper Scissor Shoot: ")
print(Game)
computer = ["Stone", "Paper", "Scissor"]
computer = random.choice(computer)
print(computer
if (Game==computer):
  print("Draw")
elif (Game=="Stone" and computer=="Paper"):
  print("You Lose") 
elif (Game=="Stone" and computer=="Scissor"):
  print("You Win")
elif (Game=="Paper" and computer=="Stone"):
  print("You Win")
elif (Game=="Paper" and computer=="Scissor"):
  print("You Lose")
elif (Game=="Scissor" and computer=="Stone"):
  print("You Lose")
elif (Game=="Scissor" and computer=="Paper"):
  print("You Win")
else:
  print("Invalid Input")
