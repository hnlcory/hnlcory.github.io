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

To give you a flavor of the game, here is a



def hit_or_stand(deck,hand):
    global playing 
    
    while True:
        x = input("Would you like to Hit, Stand or Double Down? Enter 'h', 's' or 'd'\n")
        
        if x[0].lower() == 'h':
            hit(deck,hand)  

        elif x[0].lower() == 's':
            print("Player stands. Dealer is playing.")
            playing = False
        
        elif x[0].lower() == 'd':
            print('Double Down. 2x the bet and only 1 more card')
            zzz = True
            hit(deck,hand)
            playing = False

        else:
            print("")
            continue
        break

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
    

#game scenarios
def player_busts(player,dealer,chips):
    if zzz == True:
        print('2x Bust')
        chips.lose_bet()
        chips.lose_bet()
     
    else:
        print(Fore.RED +"\n%s busts" % (playername))
        chips.lose_bet()
    
def player_wins(player,dealer,chips):
    print(Fore.GREEN +"\n%s wins" % (playername))
    chips.win_bet()

def dealer_busts(player,dealer,chips):
    print(Fore.GREEN +"Dealer busts")
    chips.win_bet()
    
def dealer_wins(player,dealer,chips):
    print(Fore.RED +"Dealer wins")
    chips.lose_bet()
    
def push(player,dealer):
    print(Fore.RED +"Tied Game. It's a push.")   
   
}



test code
Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

