Hector Motsepe @author

Installation and Preparation to lauch the Robot

First ensure that you have java and robocode framework https://robocode.sourceforge.io/ installed on your computer

You could import the robot into Robocode using the 'Import downloaded robot' from the 'Robot' menu in the game. This will import the robot into Robocode
 
You can do it like a hack, where you put the robots beside the sample robots in robocodeextract/robots or you can do it "the right way" by putting the robots in robocode/launch/robots. This way you'll be able to compile the robots when running Robocode from Eclipse/Robotcode framework. However, you  need to call the 'robocode.jar' target on the build/build.xml ant file first, and refresh the robocode/launch dir

How the robot works
Educational game with the aim to evelop a robot battle tank to battle against other tanks. Every tank is controlled by Java code
Every tank is a vehicle equipped with, A rotating gun, A rotating radar, 
The vehicle, gun and radar can, rotate independently, Initially, all aligned
Every bot has some energy (100 at start), When energy is 0 the bot is disabled, When a disabled bot is hit it is destroyed, Shooting costs energy
New energy = energy – bullet firepower
Bullet firepower is a (double) number between 0.1 and 3
Hitting an enemy bot with a bullet gives energy, Being hit takes energy, Ramming into a wall takes energy

Challenges I faced
I could not be able to install the robotcode framework, i had to run the code on online (Java),
The code didnt run because we need a software(robocode frameowrk), and convert the fie into jar
Im a python and R programmer, with a focus on data science and machine learning(AI), It was challeneging to code a robot and learn, hwoever i enejoyed the process and it was fun.
I once programmned a game with python library (Turtle) pingpong it was fun. 

THANK YOU BBD TEAM FOR THE EXPERIENCE
