#python
#美国队长的盾牌
import turtle as t
def skip(x,y):
    t.penup()
    t.goto(x,y)
    t.pendown()
skip(0,-200)
t.fillcorlor("red")
t.begin_fill()
t.circle(200)
t.end_fill()
