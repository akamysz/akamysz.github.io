---
title: Turtle Python
layout: post
---

# My Experience with Turtle Python

The very **first** time I had used Turtle Python was in class and I didn't know how to exactly feel about it.  But, after being taught *slowly* in class, I started to grasp my understanding.

## Drawing
Drawing got complicated outside of class. My initial image that I had in my head was a colorful as well as detailed bike. But as soon as I started to realize that Turtle Python has limited options for shapes, my idea of a detailed bike diminished. 

[How to Draw Circles](https://stackoverflow.com/questions/46695126/how-to-draw-circle-using-turtle-in-python-3)


----------
![ Bike ](https://lh3.googleusercontent.com/sRABN0QZMtn3eGY2VFlDM3boUVF1nRPTZaglJbS2WlWYBWFUbIHxeZ0vcRgd5oTXLcic=s134)



## In My Code
After completing the bike the first time I realized that I wanted to make the rims the same color as well as put a design in them. I had changed it but I realized that in order to have another color, I needed another turtle. After I had added my code for it, the additional code messed up my handle bars as well as chair. 
After multiple trial and errors, my code looks like this :

 1. import turtle
 2. t = turtle.Turtle() 
	 t.color('green')
 4. s = turtle.Turtle() 
	 s.color('green')
 5. a = turtle.Turtle() 
	 a.color('blue')
 6. b = turtle.Turtle() 
	 b.color('black')
*You don't want it like this:*
~~b = turtle.Turtle() b.color('black')~~
    
   

6. c = turtle.Turtle() c.color('purple')
7. turtle.speed(10)
8. print("Want to see my Bike? ") def draw_a_square(a_turtle, length):
         draw_a_polygon(a_turtle, 4, length)
    
        
9. def draw_a_polygon(a_turtle, number_of_sides, length):
        for loop_counter in range(number_of_sides):
            a_turtle.forward(length)
            a_turtle.right(float(360)/number_of_sides)
          draw a square  def draw_a_square(a_turtle):
         for loop_counter in range(4):
             a_turtle.forward(100)
             a_turtle.right(90)
            
    
10. draw_a_polygon(t, 4, 100)  s.up()  s.goto(100,100)  s.down() 
    draw_a_polygon(s, 6, 50)  draw_a_polygon(s, 10, 25) 
    draw_a_polygon(t, 100, 3)
    
    
    draw_a_polygon(t, 100, 3) s.up() s.goto(200,0) s.down()
    
    draw_a_polygon(s, 100, 3)
    
    c.right(90) c.forward(50) c.left(90) c.forward(50) c.right(90)
    c.right(90) c.forward(100) c.right(90) c.right(90) c.forward(50)
    c.right(90) c.forward(50) c.right(90) c.right(90) c.forward(100)
    c.up() c.goto(200,0) c.down() c.right(90) c.right(90) c.forward(100)
    c.right(90) c.right(90) c.forward(50) c.right(90) c.forward(50)
    c.right(90) c.right(90) c.forward(100)
    
    a.left(90) a.forward(25) a.right(90) a.forward(200) a.right(90)
    a.forward(23) a.right(90) a.right(90) a.forward(50) a.left(90)
    a.forward(20) a.right(90) draw_a_polygon(a, 20, 3)
    
    b.up() b.goto(0, 25) b.down() b.forward(20) b.left(90) b.forward(10)
    draw_a_polygon(b, 10, 3) b.right(90) b.up() b.goto(400, 400)
    
    a.up() a.goto(400, 400)
    
    c.up() c.goto(400, 400)
    
    s.up() s.goto(400, 400)
    
    t.up() t.goto(400, 400)
    
    b.up() b.goto(400, 400)
*How to draw cirlces*
# Reflection
I realized that I am not good at Python from the very start. It gets too complicated as well as frustrating when you only want to change one thing but instead, you changed everything and have to restart. Moral of the story, have everything planned out before you start writing code to save time. 
