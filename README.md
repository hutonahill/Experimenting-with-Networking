# Overview

I upgraded a GoDot game so it multiple instance could connect over a lan or on the same computer.

I write this software to contribute to the project and to learn about how networking works in GoDot.

The code is allready in its own repository so I did not include it here. Here is a link to the repository 
https://github.com/Jwursten/Pong-2

[Software Demo Video](https://youtu.be/uLYSkbAizGI)

# Network Communication

We used a combonation of peer to peer and peer to server where one peer was desinated as the host and was inchange of key elements

We used GoDot's ENetConnection.COMPRESS_NONE prodical which is layered on top of UDP

We are sending a bunch of data between instances including ball possition, paddle position, score, and player list.

# Development Environment

I used GoDot game engine which used their own gd script, and Visual Studio Code to edit.

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [GoDot Mulitplayer Video](https://youtu.be/e0JLO_5UgQo?si=pSRFsSxWD0kp0cik)
* [GoDot Documentation](https://docs.godotengine.org/en/stable/)

# Future Work

* Paddles are synced, but are not controlable. this might have somthign to do with movment limiting, keeping the paddles in designated tracks.
* currently the score mid game does not update.
