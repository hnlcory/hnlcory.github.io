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

<img class="ui medium right floated rounded image" src="https://hnlcory.github.io/images/blackjack2.png">

Cotton is a horror-esque text-based adventure game I developed using the functions and macros built from The Wizard's Game in [Conrad Barski's Land of Lisp](http://landoflisp.com/). Slightly more interesting and convoluted! (It is not that scary.)

To give you a flavor of the game, here is abreak

<div style="overflow-y: scroll; height:400px;">
def show_some(player,dealer):
    print(Fore.RED +'\n______________')
    print(Fore.RED +"Dealer's Hand:")
    print('¯¯¯¯¯¯¯¯¯¯¯¯¯¯')
    time.sleep(1)
    print(" -- Hidden --")
    print('',dealer.cards[1])
    time.sleep(1)
    print(Fore.BLUE +'\n______________')  
    print(Fore.BLUE +"%s's Hand:" % (playername))
    print('¯¯¯¯¯¯¯¯¯¯¯¯¯¯')
    print(*player.cards, sep='\n ')
    
def show_all(player,dealer):
    print(Fore.RED +'\n______________')
    print(Fore.RED +"Dealer's Hand:")
    print('¯¯¯¯¯¯¯¯¯¯¯¯¯¯')
    print(*dealer.cards, sep='\n ')
    print("Dealer's Hand =",dealer.value)
    print(Fore.BLUE +'\n______________')
    print(Fore.BLUE +"%s's Hand:" % (playername))
    print('¯¯¯¯¯¯¯¯¯¯¯¯¯¯')
    print(*player.cards, sep='\n')
    print("%s's Hand =" % (playername),player.value)
</div>







test code
Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

