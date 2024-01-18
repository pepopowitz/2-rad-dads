# Let's Get Cranking!
## Episode 5: What even is a sprite??!

1. Follow-up
   1. What have the dads been up to for the last two months?!?!
   2. What'd they get for Christmas?
2. Orient ourselves
   1. Recap of where we left off in November
3. Research reports
   1. Steve researched sprites (see below)
   2. Did Jon too?
4. Get a QR code displaying only once
5. Switch drivers??
6. Wrap it up
   1. What did we learn?


## Steve's research notes

- https://help.play.date/developer/designing-for-playdate/#sprites
   > For the purposes of this document, we’ll consider “sprites” as playable characters, NPCs, and other moving, visible entities in your game.
- https://devforum.play.date/t/screen-redraw-and-text/10951/4
- https://www.youtube.com/watch?v=8OCebUVKlb4
  - I don't think we can watch this on stream
  - Everything you need to know about sprites in the Playdate SDK
    - SquidGod: https://www.youtube.com/@SquidGodDev
  - "for anything you draw to the screen, sprites are a good option because
     1. you can explicitly set z index
     2. performance improved since the sprite only redraws when the image has changed in some way
     3. sprite code can be self-contained, i.e. OOP
  - "drawing is done relative to the sprite, not to the screen"
- drama! confusion! fight! https://www.smwcentral.net/?p=viewthread&t=92861
- another video we can't watch: https://www.youtube.com/watch?v=sheOZ-Dlleo&t=17s
  - mentions that people use "sprite" to mean both the sprite images themselves, and the objects they represent...and there is murkiness.
- https://gamedev.net/forums/topic/299806-game-objects-sprites-has-a-or-is-a/2902692/
  - "it all depends on how you define a sprite"   
- https://www.reddit.com/r/gamemaker/comments/jkkppv/sprites_vs_objects/
- https://remarkablecoder.com/sprites-in-games/
   > Sprites are two-dimensional images or animations overlaid into a scene. They are the non-static elements within a 2D game, moving independently of the background. Often used to represent player-controlled characters, props, enemy units, etc., sprites can be composed of multiple tiles or smaller sprites.
- https://devforum.play.date/t/performance-sprites-vs-primitives/7375
