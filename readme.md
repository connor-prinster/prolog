# Adventure Game in Prolog

## Running
To start the program at the beginning, you MUST type `play.`. This will start the program in your bedroom. You must exit the program to start over though.

## Playing

The way to function through the program is to use functions.
* to find where you are, you would type `where.`.
* to look around 'Your bedroom', you would type `look("Your bedroom").`. This function allows you to look at your current location.
* to study an alien figurine in 'Your bedroom', you would type `study("alien figurine").`.
* to move to 'Hallway' outside 'Your bedroom', you would type `move("Hallway")`
* to take an alien figurine, you would type `take("alien figurine").`.
* to check your inventory, you would type `intentory.`


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


## Requirements

Action | Effect | Required Condition |
--- | --- | --- |
transfer | moves a disk from one pylon to a second pylon | The motion must be legal according to the rules for towers of Hanoi

