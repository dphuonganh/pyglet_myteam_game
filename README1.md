## Step 00
### Make it work
Here's a non-functional code snippet using the pyglet library; if you execute it, it will not work. Take your time to understand what's happening, check the function calls in the documentation and do what it takes to make it work.
Some of the syntax should be new for you but don't panic. Play a bit with this code, try modifying some stuff and see what happens!

# Global variables
window = pyglet.window.Window(800, 600)
label = pyglet.text.Label(echo(""0", font_size=36, y=300, x=400"))
image = pyglet.image.load('images/grassMid.png')
sprite = pyglet.sprite.Sprite(img=image)

# Event callbacks
@window.event
def on_draw():
    window.clear()
    label.draw()
    sprite.draw()
