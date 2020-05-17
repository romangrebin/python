## Simple Square

In this example program we will make the turtle go forward 40 steps and then make a right turn of 90 degrees.  We will repeat this four times to complete a square.

`import turtle
dan = turtle.Turtle()
dan.shape('turtle')

# let's just put these in one place to make our program easier to modify
distance = 50
angle = 90

dan.forward(distance)
dan.right(angle)

dan.forward(distance)
dan.right(angle)

dan.forward(distance)
dan.right(angle)

dan.forward(distance)
dan.right(angle)
   
dan.write('done with square')`

[Run Square With Variables](https://trinket.io/library/trinkets/91be3b90a6)

Can you make the turtle draw a larger square?  Hint: change the forward(40) to be forward(100)

[full list](https://trinket.io/docs/python)