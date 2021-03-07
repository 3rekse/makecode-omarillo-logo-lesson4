### @explicitHints true

# Turtle Logo - Lesson #3

## Turtle Logo - Lesson #3 @unplugged
**Making the Turtle Turn.**

In this lesson you will make your **Turtle** turn.
![Hello, World!](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson3/raw/main/assets/turn_screenshot.png)

## Step 1
** Follow Along**

Once again, all our programs begin with an ⇢``on start``⇠ block. Then you need to add the **Turtle** using the ⇢``show turtle``⇠ block.
```blocks
turtle.showTurtle()
```

## Step 2
** Follow Along**

In the last lesson you learned to move the **Turtle** forwards or backwards.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
turtle.moveTurtleDirection(TurtleDirection.Backward, 50)
```

## Step 3
** Follow Along**

To turn the Turtle you will use the ⇢turn turtle right 90 °⇠ block and place it inside the ⇢on start⇠ block after a move block.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
turtle.moveTurtleDirection(TurtleDirection.Backward, 50)
turtle.turnTurtleDirectionByDegrees(TurtleTurnDirection.Right, 90)
```

## Step 4
** Follow Along**

At the moment it looks like nothing has happened. That is because the **Turtle** has turned, but you need to move it to see that it has turned. Add another move turtle forward 25 steps⇠ block after the ⇢turn turtle right 90 °⇠ block.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
turtle.moveTurtleDirection(TurtleDirection.Backward, 50)
turtle.turnTurtleDirectionByDegrees(TurtleTurnDirection.Right, 90)
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
```

## Step 5
** Try it Out**

Notice the *right* in the block. The direction can be changed to turn the **Turtle** right or left. Try turning the **Turtle** left.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
turtle.turnTurtleDirectionByDegrees(TurtleTurnDirection.Left, 90)
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
```

## Step 5
** Try it Out**

Now try moving the **Turtle** some different distances, different directions and now turning it as well.
```blocks
turtle.showTurtle()
turtle.moveTurtleDirection(TurtleDirection.Backward, 25)
turtle.turnTurtleDirectionByDegrees(TurtleTurnDirection.Right, 90)
turtle.moveTurtleDirection(TurtleDirection.Forward, 50)
turtle.turnTurtleDirectionByDegrees(TurtleTurnDirection.Left, 90)
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
```

## Step 6
**Success!**

You can now make the **Turtle** turn right and left.

## Step 7
**Your Turn**

Get your **Turtle** to move, turn and then say, "I can change direction!"

## Step 8
**Done**

You have successfully completed your third lesson in Turtle Logo.

```ghost
turtle.say("Hello, World!")
```
