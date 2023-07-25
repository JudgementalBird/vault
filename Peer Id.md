#stormworks #multiplayer #singleplayer 
##### Peer Id keeps track of players in the same game.
If you are in singleplayer, you are considered the host, and so your peer id is locked to 0.
If you are in multiplayer, you can view your peer id by opening the player list.
For me this is opened with the button between tab and esc, for you it might be something else.
If you can't find the button, go into Settings -> Controls, and look for "Player List" under "MULTIPLAYER", then change it to a button you know.

FYI:
Peer id -1 is usually used to refer to all players, or the whole server.
Peer id 0 usually refers to the host.
The peer id of a joining player is the peer id of the last player to join, plus 1.
The peer ids in a server are not guaranteed to be continual at any moment in time, you can end up with for example peer ids 2,6,11 in a game if people join and then leave.