import random

def GameWin(comp,you):
    if comp == you:
        return None
    if comp == 's':
        if you == 'w':
          return False
        elif you == 'g':
            return True

    elif comp == 'w':
        if you == 's':
            return True
        elif you == 'g':
            return False

    elif comp == 'g':
        if you == 'w':
            return True
        elif you == 's':
            return False


print("comp turn: Sanke(s) Water(w) Gun(g)?")
randNo = random.randint(1, 3)
if randNo == 1:
    comp = 's'
elif randNo == 2:
    comp = 'w'
elif randNo == 3:
    comp = 'g'


you = input("your turn: Snake(s) Water(w) Gun(g)?")
a = GameWin(comp,you)
if a == None:
    print("Game is tie")
elif a:
    print("You win the Game")
else:
    print("You lose the Game")


