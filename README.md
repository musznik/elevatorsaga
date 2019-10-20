Elevator Saga M1
===================
The elevator programming game

Now you can call own function from the game
```
{
    my_custom_function : function(elevators){
        return elevators;
    },
    init: function(elevators, floors) {
        ...
        var my_object = window.game.my_custom_function(elevators);
    });
    ...
```


[Play it now!](http://play.elevatorsaga.com/)

Or [Run the unit tests](http://play.elevatorsaga.com/test/)
Please report any test failures as an issue.

![Image of Elevator Saga in browser](https://raw.githubusercontent.com/magwo/elevatorsaga/master/images/screenshot.png)
