import random
choices =[" Rock ", "Paper" ,"Scissors"]
computer =random.choice(choices)
players = False
cpu_score = 0
players_score = 0
while True :
  players =input("Rock ,Paper,Scissors-:-").capitalize()
  if players == computer:
    print("Tie:")
  elif  players == "Rock" :
    if computer == "Paper" :
      print("You lose", computer, "covers", players)
      cpu_score +=1
    else:
      print("You win",players , "smashes ", computer )
      players_score +=1
  elif  players == "Paper" :
    if computer == "Scissors" :
      print("You lose", computer, "covers", players)
      cpu_score +=1
    else:
      print("You win",players , "smashes ", computer )
      players_score +=1
  elif  players == "Scissors" :
    
    if computer == "Rock" :
      print("You lose", computer, "cut", players)
      cpu_score +=1
    else:
      print("You win",players , "cover", computer )
      players_score +=1

  elif players== 'End':
      print("Final Scores:")
      print(f"CPU:{cpu_score}")
      print(f"Plaer:{players_score}")
      break

  

  
              
  
