# Online-TicTacToe
Online Multiplayer TicTacToe using Python with multithreading for simultaneous multiplayer match

This project is part of my IPC assignment in which I was tasked to create an "online" multiplayer tictactoe game utilizing the concept of distributed system. In this project I learned how to use multithreading in order to host multiple match at once. Both server and client communicate using TCP protocol in order to make sure no match data is lost.



In order to use this code you need a minimum of two PC to test out the "online" capability. One PC can be used as both server and client while the other must be client. Or you can have another case where one PC is used as game server and other two PC is used as a clinet. If another PC tries to connect to the server after one match is created, the server created another thread to host that other game. After that, the server will wait for another player so the match can start.



If you want to test out the code, make sure to edit the IP in both tictactoeClient and tictactoeServer. If a PC is used as both server and client, keep the IP as localhost. If the PC is used as a client, edit the IP to match the IP of the server.
