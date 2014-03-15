#####Download
- [OSX 64-bit](https://www.dropbox.com/s/6nlji9u81q0yjyf/AngryBotsInAiWorld_x64.app.zip)
- [OSX 32-bit](https://www.dropbox.com/s/um0cw1r1da8dqg8/AngryBotsInAiWorld_x86.app.zip)
- [Windows 64-bit](https://www.dropbox.com/s/3atnk5pvlao9m7w/AngryBotsInAiWorld_x64.exe.zip)
- [Windows 32-bit](https://www.dropbox.com/s/f2fyoz3doql702a/AngryBotsInAiWorld_x86.exe.zip)

#####API

Send an action to receive an image from both eyes, i.e.:

_Player 1_<br>
`http://localhost:1235/?shoot=False&move_x=0.42&move_y=-0.42&look_x=-0.42&look_y=0.42&jump=True`

<img src="http://i.imgur.com/4RkNGEE.png"/>

_Player 2_<br>
`http://localhost:1236/?shoot=False&move_x=0.42&move_y=-0.42&look_x=-0.42&look_y=0.42&jump=True`

<img src="http://i.imgur.com/thy5JUh.png"/>

**Parameters**

Name       | Action                    | Type                      
---------  | -------------------       | -------------------------- 
move_x     | Strafe                    | Float between -1.0 and 1.0 
move_y     | Move forward, backward    | Float between -1.0 and 1.0 
look_x     | Look left, right          | Float between -1.0 and 1.0 
look_y     | Look up, down             | Float between -1.0 and 1.0 
shoot      | :boom:                    | Boolean True or False      
jump       | Currently disabled        | Boolean True or False      

#####Examples:

[random_bot.py](https://github.com/aiworld/AngryBotsInAiWorld/blob/master/examples/random_bot.py)

[twirling_bot (web - coffeescript)](https://github.com/aiworld/AngryBotsInAiWorld/tree/master/examples/twirling_bot)

#####TODO
- Allow changing image sizes
- Renable jump after fixing rampant falling of the edge of world
- Turn off development mode in unity build

