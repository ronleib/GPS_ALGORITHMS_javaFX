# Ex4 Kill The Terrorist
This  project represents a Game based a graph-theory algorithms and java Gui Implemenatation 
 the method's referee to an directional weighted graph , where every vertex is a Gps Coordinate .
 You can see in the graph a road-system or communication with a terrorist on it and a force that is moving that can kill the terrorist 
 There are two main game modes one is Manual and the other is automatic.
  @author  Simon Pikalov and Ron Leib
  
 
 Main features : 
  -  
  - Gui Based Game with interactive control's
  - Export a Kml to a Google earth format 
  - Manual Game based on mouse clickes
  - Automatic  Game based on Dijkstra Algorithm
  -show statistics from server 
 

  
### Installation
To Run the Game you must have the JavaFx Sdk if your using intellij it should come pre instaled otherwise 
check this repo for the SDK :  https://gluonhq.com/products/javafx/ 

Then 
Pull the file from the Git repository with the command : 
```sh
$ git clone https://github.com/simon-pikalov/GPS_ALGORITHMS_javaFX.git

```

# The gui Package 
![](photoLib/uml2.png)

### The Gui Class : 
This class represent a Gui as JavaFX Application of the Game Catch The Terrorist
This class can be changed to Draw all the games the iplement Gamable Interface,
The Game presented Here Show a Menu at start when you choose a game mode and afterword's
you can choose a game mode automatic or manual and start tha game at ich mode.
Main method's  : 
- start
- drawGame
- onUpdate
- ManualGame
- play
- statistic


# The gameClient Package 
![](photoLib/uml.png)

### The killTheTerrorist  Class : 
 * This class represent a Utils for the game  catch The Terrorist.
 * The  class communicate with the server to send and receive data from it ;
 * This game uses Datastucture method's such as shortest path and more for the game algorithm
 * 
Main method's  : 
- Automaticplay
- builderGame
- DistDest
- getGameGraph
- initFruits
- Manualgame
- chechFastMil
SamCatchRon
### The Robot  Class : 
This class Implement Robot interface and it's an inctence of
an Object Type That "Catch" Anothe object in a
a Gamable Inetefece That can be geted from a server.

Main method's  : 
- robot
- getID
- getLocation
- getNextNode
- setNextNode
- setLocation
### The Fruit  Class : 
This Class represent a Object Type fruit the implement's fruit's interface
That " neede to be Catched " by onother object in a
Gamable Inetefece That can be geted from a server
Main method's  : 
- getType
- getLocation
- fruit


# Game instructions : 


#### First of all You can Login (optional) :

 ![](photoLib/login.png)
 
 
  #### Then to the game will start  : 
  
   ![](photoLib/open.png)
 
 ####  To play  select a scene : 
 
  ![](photoLib/menu.png)
 
  ####  Then chose a Game mode : Automatic or manual , if Your on Manual pres the tank and the a number to move if your on Auto no Actions is needed  : 
  
  
   ![](photoLib/game.png)
   
 #### To view statics's press the statics's button   : 
     
  ![](photoLib/statistics.png)
   
   

