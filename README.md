# game-python



from random import randint
def game(over):
    print over , "good job!"

def twelfth_stair():
    print"CONGRATULATIONS"
    print "you win"
    print"if you wish to play again please start here>>>>>>>>>"
    introduction()

def eleventh_stair():
    print"there is a deadly snake in this stair(eleventh),after you answer the below question,you go back to third stair"
    d1 = raw_input("what is the most crowded country in the world")
    if d1 == "china":
        third_stair()
    else:
        game("you lose the game")

def tenth_stair():
    print"beeeee carefullllll wow it was a small snake you will go back to eighth stair but firstly ypu should answer this question,here you are"
    c1 = raw_input("who was the inventor of the electricity?")
    if c1 == "edison":
        eighth_stair()
    else:
        game("game over")

def nineth_stair():
    print"nineth,just three stairs to success"
    raw_input(" press enter to throw the dice")      
    a1 = randint(1,6)
    if a1 == 1:
	    tenth_stair()
    elif a1 == 2:
        eleventh_stair()
    elif a1 == 3:
        twelfth_stair()
    elif a1 == 4:
        nineth_stair()
    elif a1 == 5:
        nineth_stair()
    else:
        nineth_stair()

def eighth_stair():
    print"a small snake is seeing you!!!!,eighth"
    raw_input(" press enter to throw the dice")    
    a1 = randint(1,6)
    if a1 == 1:
	    ninth_stair()
    elif a1 == 2:
        tenth_stair()
    elif a1 == 3:
        eleventh_stair()
    elif a1 == 4:
        twelfth_stair()
    elif a1 == 5:
        eighth_stair()
    else:
        eighth_stair()

def seventh_stair():
    print"notice!!! you are near a ladder,seventh stair"
    raw_input(" press enter to throw the dice")
    a1 = randint(1,6)
    if a1 == 1:
	    eighth_stair()
    elif a1 == 2:
        ninth_stair()
    elif a1 == 3:
        tenth_stair()
    elif a1 == 4:
        eleventh_stair()
    elif a1 == 5:
        twelfth_stair()
    else:
        seventh_stair()

def sixth_stair():
    print"PYTHON SNAKE"
    print"you have been beated by python you will be taken to first stair!!!! but before that you have to answer the question that you will be asked"
    b1 = raw_input("WHEREis the capital of afghanistan?")
    if b1 == "kabul":
        first_stair()
    else:
        game("opsssss it is the end you could not!!!!")
def fifth_stair():
    print"oopss you are very close to a killer snake,fifth stair"
    raw_input(" press enter to throw the dice")
    a1 = randint(1,6)
    if a1 == 1:
	    sixth_stair()
    elif a1 == 2:
        seventh_stair()
    elif a1 == 3:
        eighth_stair()
    elif a1 == 4:
        ninth_stair()
    elif a1 == 5:
        tenth_stair()
    else:
        eleventh_stair()

def fourth_stair():
    print"it is the fourth stair,continue!!!"
    raw_input(" press enter to throw the dice")
    a1 = randint(1,6)
    if a1 == 1:
	    fifth_stair()
    elif a1 == 2:
        sixth_stair()
    elif a1 == 3:
        seventh_stair()
    elif a1 == 4:
        eighth_stair()
    elif a1 == 5:
        nineth_stair()
    else:
        tenth_stair()

def third_stair():
    print"in third stair you will be promoted to seventh stair with a ladder"
    seventh_stair()

def second_stair():
    print"here is second stair"
    raw_input(" press enter to throw the dice")
    a1 = randint(1,6)
    if a1 == 1:
	    third_stair()
    elif a1 == 2:
        fourth_stair()
    elif a1 == 3:
        fifth_stair()
    elif a1 == 4:
        sixth_stair()
    elif a1 == 5:
        seventh_stair()
    else:
        eighth_stair()
def first_stair():
    print"you are at the first stair"
    raw_input(" press enter to throw the dice")
    a1 = randint(1,6)
    if a1 == 1:
	    second_stair()
    elif a1 == 2:
        third_stair()
    elif a1 == 3:
        fourth_stair()
    elif a1 == 4:
        fifth_stair()
    elif a1 == 5:
        sixth_stair()
    else:
        seventh_stair()

def start_point():
    raw_input(" press enter to throw the dice")
    a1 = randint(1,6)
    if a1 == 1:
	    first_stair
    elif a1 == 2:
        second_stair()
    elif a1 == 3:
        third_stair()
    elif a1 == 4:
        fourth_stair()
    elif a1 == 5:
        fifth_stair()
    else:
        sixth_stair()
def introduction():
    print"SNAKE AND LADDER"
    print"in this challenge you have to reach the twentieth stair of a castle to acquire a valuable gain"
    print"whenever you are beaten by a snake, you should answer a question,if not,you will be defeated by that snake"
    start_point()
introduction()  
