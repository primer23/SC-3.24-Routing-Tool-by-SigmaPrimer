# SC-3.24-Routing-Tool-by-SigmaPrimer
A attempt at making a cargo routing tool for the new cargo missions in 3.24. 

Hey everyone! 
With the new cargo missions in 3.24, the only major issue I have with them (apart from all the obvious bugs) is the lack of organising or routing available in the mobiglass app. I couldnt find a good enough solution so I decided to test myself and make my own! Here is version 1 for you all :) This tool allows you to add all your accepted missions and commodity types/amounts with the locations and select a starting location. From here you can load multiple missions into the tool and then click route calculate optimal route. It will then take all the mission data inputed and calculate an approximate optimal route to take for drop of and picking up of cargo. This works of a nearest neighbour system with some logic involved. 

Current Limitations/Known Bugs:
- There is currently an issue with the heirachy of locations which cause planetary locations to not properly. I am actively investigating how to resolve this. For the time being please use this tool for solar and interstellar routes.

How to use: 
1. In game grab some missions (preferably interstellar and solar missions) 
2.  The interface is quite straight forward. First thing to do is select the mission type (Solar/Instellar for this release) 
3. Next select mission type:
- Direct - From one location to another
- Multi drop off - From one pick up location to multiple drop off locations
- Multi pick up - From multiple pick up locations to one drop off locaiton
3. Add the drop off location/s and pick up locations/s aswell as commodities and amount.
  - To add more commodities or locations click the "add commodities" and "add another drop off/pick up location" 
4. Once you have populated the missions click "add missions. This will add the mission to the table along with the the relevant data.
5. Continue to fill in the missions that you have grabed in game.
6. Select a starting location (this is where you are in game currently or closest POI)- it is not really necessary you can set this to your first pick up point and it will work the same. 
6. Finally click "Calculate Optimized Route"
7. This will tell you your optimal route for your missions, along with what commodity to drop off and pick up at each location.

This is my first time developing such a tool so any feedback is highly appreciated! Will also try to continue to improve the tool for the future (or until CIG adds the functionality into the game lol) 

Thanks Everyone :)
