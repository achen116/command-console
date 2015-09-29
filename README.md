# Command Console

Implement an interactive console for editing a particular object. The console should allow you to enter a string after which it will return the appropriate response (very similar to a terminal session). The following commands need to be implemented:

* SET propertyname=value: Assigns the value “value” to the object’s member named “propertyname”. If the input value is incompatible (i.e. an int being set to a string), print out an appropriate error message.

* GET propertyname: Display the current value of the object’s “propertyname” member

* GET *:  Display all the object’s members and their current values.

The system should be easy to extend with future commands and should accept any object, so other developers can use the interactive console to edit their own objects correctly.
