# import turtle

def draw_flower():
    # create a turtle object
    t = turtle.Turtle()
    t.speed(10)

    # draw the petals of the flower
    for i in range(36):
        t.left(10)
        t.forward(100)
        t.right(160)
        t.forward(100)

    # hide the turtle
    t.hideturtle()

draw_flower()

