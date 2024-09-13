# fuzzy-journey
def make_square():

    turn_left()

    move()

    turn_right()

    move()

    turn_right()

    move()

    turn_right()

    move()

    turn_right()

   

def turn_right():

    turn_left()

    turn_left()

    turn_left()

   

def next_square():

    turn_right()

   

def row_square():

    next_square()

    turn_left()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    move()



def row_square1():

    next_square()

    turn_left()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    move()



def top_column():

    to_next_column()

    row_square()

    row_square()

    row_square()

    row_square1()

   

def to_next_column():

    next_square()

    move()

    move()

   



def square_below():

    move()

    move()

    next_square()

    move()

    next_square()

    move()



def next_column():

    next_square()

    square_below()



def Make_Square_Column():

    make_square()

    move()

    move()

    next_square()

    make_square()

    move()

    move()

    next_square()

    make_square()

    move()

    move()

    next_square()

    make_square()

    move()

    move()

    next_square()

    make_square()

    move()

   

def right_column():

    next_square()

    turn_left()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    move()

def bottom_column():

    row_square1()

    next_square()

    turn_left()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    move()

    next_square()

    turn_left()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    move()

    next_square()

    turn_left()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    move()

    move()

   

def full_right_column():

    right_column()

    right_column()

    right_column()

def linear_move():

    turn_right()

    move()

    move()

    move()

    move()

    move()

    move()

    move()

    turn_right()

    move()

    move()

def midtop_column():

    row_square()

    row_square()

    row_square()

def linear_move2():

    move()

    turn_right()

    move()

    move()

    move()

    move()

    move()

    turn_right()

    move()

    move()

def bottom_square():

    next_square()

    turn_left()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    next_square()

    move()

    move()

def midbottom_row():

    bottom_square()

    bottom_square()

    bottom_square()

   

Make_Square_Column()

top_column()

full_right_column()

bottom_column()

linear_move()

midtop_column()

linear_move2()

midbottom_row()

move()

turn_right()

move()

move()

move()

turn_right()

move()

move()

midtop_column()

move()

turn_right()

move()

turn_right()

move()

move()

move()

move()

move()

move()

move()

move()

turn_left()

