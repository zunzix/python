style = input("Choose a style:\n 1. Comedy\n 2. Tragedy\n 3. Adventure\n")

person = input("Enter a name: ")
animal = input("Enter an animal: ")
color = input("Enter a color: ")
building = input("Enter a building: ")

if style == "1" or "Comedy" or "comedy" or "COMEDY":
  print("There once was a genderless person named " + person + ".\n They went to a"+ building +" and met a "+ animal +", which was "+ color + ".\n Then the "+ animal +" said: 'Airplane food, am I right?'")

elif style == "2" or "Tragedy" or "tragedy" or "TRAGEDY":
  print("You walk into "+ building +" as you witness "+ animal +" snapping one of your crewmates neck.\n You run to the body, and report it.\n In the meeting you say that it was "+ animal +", who snapped "+ color +"'s neck.\n But the imposter says it's you, "+person+", and alas, you got voted out." )

elif style == "3" or "adventure" or "Adventure" or "ADVENTURE":
  print("The Horrible Demon King has finaly been defeated by "+ person +" and his trusty "+ color + " "+animal+ ". They are gathering at the " + building+ " to celebrate their victory!")
else :
  print("You screwed up typing the story theme, damn bro.")
