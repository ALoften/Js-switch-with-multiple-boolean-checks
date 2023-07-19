# Js-switch-with-multiple-boolean-checks
The script below allows you to use multiple boolean checks in one switch statement by combning any results you are looking for into one result. With booleans, its just adding them, but with multi-variable types, I prefer converting them to strings.

The reason why this is important is because switch statements normally read very clearly. Though on average I prefer using if-statements, using a switch statement could be very important as well. For example, when creating a video game, sometimes it is important to create a state-manager to detect things like "level"(we would probably call it a level-manager here but the style of coding used would be known as a state manager).

In the above example, you may want to check if the level is equal to "not started", "1", "2"..."finished". Depeneding on the state, you may want to do different things. For example, if the player unlocked bonus material that leads to an extra cutscene, you could check if "level == 2 + bonusMaterialUnlocked == true" which would allow you many more flexible programming solutions and would keep each state(or level) manageable.

Live example...

[jsFiddle](https://jsfiddle.net/x_sus/m8jgohk6/3/)

Live example using above game scenario...

[jsFiddle](https://jsfiddle.net/x_sus/rosbepu1/)

