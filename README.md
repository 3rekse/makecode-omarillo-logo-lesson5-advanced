### @explicitHints true

# Turtle Logo - Lesson #5 - Advanced

## Turtle Logo - Lesson #5,with variables and sprites @unplugged
**Making the Turtle's Pen Move Up and Down.**

In this lesson you will make the **Turtle Objects** lift it's pen up and down.
![color](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson5-advanced/raw/main/assets/pen_up_screenshot.png)

## Step 1
Code your solution below.

```ghost
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.moveDirection(TurtleDirection.Forward, 25)
myTurtle.turnDirectionByDegrees(TurtleTurnDirection.Right, 90)
myTurtle.setPenColor(0)
myTurtle.pen(TurtlePenMode.Up)
myTurtle.say("Hello, World!")
```
