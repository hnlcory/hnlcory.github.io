---
layout: project
type: project
image: images/blackjack1.png
title: Blackjack
permalink: projects/blackjack
# All dates must be YYYY-MM-DD format!
date: 2020-06-08
labels:
  - Python
  - GitHub
summary: A text version of Blackjack created in my first College CS course
projecturl: https://hnlcory.github.io/projects/blackjack
---

<div style="overflow: auto; max-height: 80vh; background-color: white;">
<img class="ui medium right floated rounded image" src="https://hnlcory.github.io/images/blackjack2.png">
 Blackjack was the first major project I had in a College level Computer Science course. This class ICS110 was offered by the University of Hawaii - Maui over the summer of 2020. This class primarily focused on developing python skills as well as general coding habits.<br><br>

The game was coded in Python with the use of Repl.it for lightweight development, and allows for the game to run on laptops, desktop computers, and mobile devices. The main interface includes color distinctions between the AI and Player. The player begins with 100 chips and has the ability to wajor a certain amount of chips every game. In the event of a loss, the player loses chips, and loses the game when they no longer have any to wajor.<br><br>

Card data is stored within its own class, and the player’s hand is stored in a Hand class. A snippet of the Hand class is shown below:<br><br>
<pre>
  <code>
class Hand:
 # starter values
   def __init__(self):
       self.cards = [] 
       self.value = 0  
       self.aces = 0    # keep track of aces
  
   def add_card(self,card):
       self.cards.append(card)
       self.value += values[card.rank]
  
   def adjust_for_ace(self):
       pass
</code>
</pre>

The user is able to Hit, Stand or Double Down whenever it is their turn. Normal blackjack rules apply to the game. Once the game ends, the dealer’s hidden card is revealed to the player. As my first sucessful large project, it is a key milestone towards my degree in Computer Science.<br><br>


Source: <a href="https://replit.com/@hnlcory/Project-2-Cory-Parker#main.py"><i class="large github icon"></i>Blackjack Game</a>
</div>










