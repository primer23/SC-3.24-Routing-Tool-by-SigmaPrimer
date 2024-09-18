# SC-3.24-Routing-Tool-by-SigmaPrimer
A attempt at making a cargo routing tool for the new cargo missions in 3.24. 

Hey everyone! 
Im back again with an early test of a new and improved cargo routing system. Ive managed to make it look a bit cleaner now. And interacted a couple of new things. This model is only for solar or interstellar deliveries (no planetary missions yet unfortunately, but definitely once I get this one working to where I want it its on the back burner :( ).

This is basically a completely new code with a model called a genetic appraoch (quite interesting if you dont come from a computer science background). The same functionality as the last version still applied but there are now accurate coordinates and distances between points. The route data is more optimised aswell for some basic cargo management(which mission its part of and where did the cargo come from). he algorithm is a tricky thing to implement, with alot of constrainsts and parameters that ive aded through some logical thinking about what we face in game. So this period will be basically to see how it generates results for different scenarios and hauling routes. Id love some real in game feadback about if you try one of these routes (do you feel like it helps you organise things?, is the routing a bit weird?) Will be planning to add some more features to this model and to keep improve its funcitnoality  

Next feature will be setting ship SCU limites and quantum speed/quantum fuel as another constraint. Also i am looking into dynamic population of the route with new missions aswell. (Unfortunately there isnt a delete or clear button in this version please just refresh the page to reset the tool). Let me know what other features i can add in aswell. 
Happy Hauling


How to use: 
1. In game grab some missions (interstellar and solar missions) 
2.  The interface is quite straight forward. First thing to do is select yoru starting location
3. Next select mission type:
- Direct - From one location to another
- Multi drop off - From one pick up location to multiple drop off locations
- Multi pick up - From multiple pick up locations to one drop off locaiton
3. Add the drop off location/s and pick up locations/s aswell as commodities and amount as well as how much money you recieve per mission. 
  - To add more commodities or locations click the "add commodities" and "add another drop off/pick up location" 
4. Once you have populated the missions click "add missions. This will add the mission to the table along with the the relevant data.
5. Continue to fill in the missions that you have grabed in game.
6. Finally click "Calculate Optimized Route" (yo ucn tweak the parameters available for the model to allow it have more generations to see if you can produce an even more optimsied pathing. 
7. This will tell you your optimal route for your missions, along with what commodity to drop off and pick up at each location.


