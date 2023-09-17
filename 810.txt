'''Implement a class called player that represents a cricket player .
method called play () which prints "The player is playing cricket. Derive two classes, Batman and 
Bowler, from the player class . overridde the play() method in each derived class to print "The batsman
is batting " and "The bowler is bowling",respectively . Write a program  to create objects of both the 
Batsman and Bowler classes and call the play() method for each object. '''


# Define the base class player
class player:
  def play (self):
    print ("the player is playing cricket.")

# Define derived class Batsman 
class Batsman (player):
  def play (self):
    print ("The batsman is batting  ")
    
#Define  derived class Bowler 
class Bowler(player):
  def play(self):
    print("The bowler is bowling.")

# create objects of Batsman and Bowler classes 
batsman = Batsman()
bowler = Bowler()

# call the play() methods for  each other 
batsman. play()
bowler.play()

  
    
  