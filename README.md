# Multiplayer Tic Tac Toe 

## A LAN game developed using Java Socket & Multithreading where users can create custom rooms & play simultaneously.
## Player can join from any platform (Windows, Linux or Mac).


•	 The unique feature of this project is that it allows multiple pair of players to play game concurrently.

•	 Game allows the players either to create a virtual game room or to join a virtual game room.

•	 When player choose to create a game room then system will generate a room which contains a unique name.

•	 When player choose to join a game room then system will ask for the game room name and once user enters it, he will be entered in that room where he can play against the other 
player who created that room.

•	 Once the game will get over, system will destroy that particular game room and then same name room will be available for re-creation.

## Instructions : -


1) First Run the Server file by writing `java Server` in your command prompt. Your Server has been started and your are good to go.

2) Now to play games between multiple players open command prompt in any computer which is in same network as the computer running `Server.java`. Then type `java Client` and Enter the IP address of Server, Which will start the game. Here you have 2 options :- Create Room or Join Room.

3) If a person has already created the room then you can join that room OR you can create your own room. If a room with already same name exists the you can not create the room with that name. To join the room you will have to give the name of the room that you want to join.

4) If you have created the room, Your game will not start until someone has joined your room. Once a person has joined your room the game will begin. After the game has been finished the room will be destroyed and name of that room is available.

###### Note :- You can create any numbers of rooms concurrently. 

#### This is the Compilation Sequence

1. Compile the Client.java file,
2. Then compile TicTacToe.java file,
3. Then compile Server.java file,
4. Then compile Room.java file,
5. And lastly compile Player.java file.


### The Sequence of execution.

##### Here I have used 127.0.0.1 as IP adrress because Server.java was running on the same computer as the Client.java


### Here's the Screenshot Of Game
<img width="1120" alt="Player Wins" src="https://github.com/rahulshah08/Tic_Tac_Toe/assets/77283801/6cf8a4b7-5d8e-4d6c-a7da-ce2aef17922d">

