# suprice
файл сюрьприз для вашей девушки или же можно поменять под себя
import turtle
from turtle import *

turtle = turtle.Turtle()

color ('red')
begin_fill()
pensize(3)
left(50)
forward(133)
circle(50,200)
right(140)
circle(50,200)
forward(133)
end_fill()

# чисто для красоты

turtle.penup()
turtle.right(180)
turtle.forward(90)
turtle.right(-90)
turtle.forward(25)
turtle.pendown()

# font "шрифт" "размер"

turtle.color("red")
turtle.write("Я люблю тебя ТУТ ИМЯ <3", font=("Mono", 16, "normal"))
