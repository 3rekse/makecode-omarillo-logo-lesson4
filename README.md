### @explicitHints true

# Omarillo Logo - Lesson #4

## Omarillo Logo - Lesson #4 @unplugged
**Making the Omarillo's Pen Change Color.**

In this lesson you will change the color of the trail the **Omarillo** leaves.
In questa lezione cambierai il colore della scia lasciata dall'**Omarillo**.
![color](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson4/raw/main/assets/color_screenshot.png)

## Step 1
** Follow Along**

Once again, all our programs begin with an ⇢``on start``⇠ block. Then you need to add the **Omarillo** using the ⇢``show omarillo``⇠ block.
```blocks
omarillo.showOmarillo()
```

## Step 2
** Follow Along**

The **Omarillo** by default leaves a white trail behind it. This color can be changed by using the ⇢set omarillo's pen color to ▢⇠ block.
L'**Omarillo** per impostazione predefinita lascia dietro di sé una scia bianca. Questo colore può essere modificato utilizzando il blocco ⇢set omarillo's pen color to ▢⇠
```blocks
omarillo.showOmarillo()
omarillo.setPenColor(1)
```

## Step 3
** Follow Along**

Inside the ⇢set omarillo's pen color to ▢⇠ block, select the "▢" and select *red*. Now add a ⇢myOmarillo move forward 25 steps⇠ block to see the new red trail.
All'interno del blocco ⇢set omarillo's pen color to ▢⇠, seleziona "▢" e seleziona *red*. Ora aggiungi un blocco ⇢myOmarillo move forward 25 step⇠ per vedere la nuova scia rossa.
```blocks
omarillo.showOmarillo()
omarillo.setPenColor(2)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 4
** Follow Along**

Puoi anche cambiare il colore più di una volta. Dopo essere andato avanti
You can even change the color more than once. After moving forwards, add another ⇢set omarillo's pen color to ▢⇠ block and change the color to *blue* then add forwards again.
```blocks
omarillo.showOmarillo()
omarillo.setPenColor(2)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.setPenColor(8)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 5
** Try it Out**

Now try moving the **Omarillo** some different distances, different directions, turning and changing color.
```blocks
omarillo.showOmarillo()
omarillo.setPenColor(8)
omarillo.moveOmarilloDirection(OmarilloDirection.Backward, 25)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Right, 90)
omarillo.setPenColor(2)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 50)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Left, 90)
omarillo.setPenColor(7)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 6
**Success!**

You can now change the trail color the **Omarillo** leaves.

## Step 7
**Your Turn**

Get your **Omarillo** to:
- move
- change its trail color
- turn
- move again
- then say, "I can change colors!"

## Step 8
**Done**

You have successfully completed your forth lesson in Omarillo Logo.

```ghost
omarillo.say("Hello, World!")
```
