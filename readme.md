# Adventure Game in Prolog

## Running
To start the program at the beginning, you MUST type `play.`. This will start the program in your bedroom. You must exit the program to start over though.

## Playing

The way to function through the program is to use functions.
* to find where you are, you would type `where.`.
* to look around *Your bedroom*, you would type `look("Your bedroom").`.
* to study an *alien figurine* in *Your bedroom*, you would type `study("alien figurine").`
* to move to *Hallway* outside *Your bedroom*, you would type `move("Hallway").`
* to take an *alien figurine*, you would type `take("alien figurine").`
* to check your *inventory*, you would type `intentory.`
* to make a *charged dragon bone*, you would type `make("charged dragon bone")` while holding a *large dragon bone* and in the *Laser Lab*.
* to put *alien figurine* in the room, you would type `put("alien figurine").`
* to transfer *small energy disk* to *red pylon*, you would type `transfer("small energy disk", "red pylon").`


## For Grader

Function        | Checked   | Unchecked 
---             | ---       | ---
look around     | look(item/place)    | lookless(item/place)
study object    | study(item/place)    | studyless(item/place)
move around     | move(newPosition)    | moveless(item/place)
pick up object  | take(item)    | takeless(item)
put down object | put(item)       | putless(item, place to put)
combine ingredients | make(item)  | makeless(item)
transfer energy disks | transfer(disk, new pylon) | transferless(disk, new pylon)

