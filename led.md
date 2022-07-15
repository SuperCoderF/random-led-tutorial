# Random Led

## Step 1

First add a toggle Led.

```blocks
basic.forever(function () {led.toggle(0, 0)
```
## Step 2

Then add the choose Random number.
and after your done press the downlod button

```blocks
basic.forever(function () {
    led.toggle(randint(0, 10), randint(0, 10))})
```
