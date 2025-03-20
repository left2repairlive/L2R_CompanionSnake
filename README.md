# Get it working
Simply download the *.companionconfig* file and import it into your Companion. **Careful, your current setup will be erased!**
You might need to start one of the triggers, as they are the game clock. 1Hz means the snake is moving a block every second, 5Hz means its moving a block every 200ms or 5 blocks each second. I found **3Hz** to be a good speed for a challenging play.
There is a `playfieldWidth` and `playfieldHeight` in the custom variables. These can be adjusted for smaller streamdecks (f.ex. 5x3), but you should also be able to create a 8x8 playfield (or larger) if you want to stack streamdecks.
