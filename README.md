# MultiClientQuizGame
This repository is an implementation of a multiplayer quiz game using socket programming which is done as part of Computer Networks course.

# Question
Develop a game , where multiuser participate in the game. Server has 5 questions with each question of four options.If the users are connected to the server, then the server starts sending the question one by one with a timestamp reply of 1 minute. If a multiuser plays the game, then the winner is decided by the server based on the average minimum time taken by a client to reply to all answers. If a client gives a wrong reply to any one of the answers, then the server sends a message to the client "Better luck next time" and terminates the connection of the client.

# Introduction
The server file was hosted on public domain, on Microsoft Azure. The IP address of the virtual machine used to establish a connection between the client and the server, just like the first question.Forking was used to create multiple simultaneous processes.In this case, the questions were asked to the clients, the time to answer the questions were measured, and written into a document , by use of c time() and file i/o operations. Thereafter, it was sorted and the client with the least time consumed was declared the winner, and everyone else loses.
