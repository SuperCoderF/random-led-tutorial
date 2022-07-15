# Random Led

## Step 1

First add a toggle Led.

```blocks
basic.forever(function () {led.toggle(0, 0)
```
## Step 2

Then add the choose Random number.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 10), randint(0, 10))})
```
## Step 3

Then press downlod and try it on your microbit!

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
