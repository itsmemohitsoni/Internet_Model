# Internet Model
    -> Made By:-
         Group 7
         Dhruv Kukreja (2021CSB1084)
         Mohit Soni    (2021MCB1238)
         Ishan Bhagat  (2021CSB1097)

This project "A BASIC INTERNET MODEL" is focused on working of the networks:-
    Here, we connect systems under a network to other systems using routers. Devices connect to routers of unique IP address through which the information stored 
    in databases is exchanged among users. Further, the information is accessed using routing tables, and they help in choosing the shortest path from your router 
    to the desired database and if the path is found successfully, the network provides you with the piece of information you want in the form of discrete data 
    packets, otherwise, if the connection establishment fails, the program shows "Server not found" on the screen.

-> How the program works?

    //To see how the project works, Please follow the instructions given below
    -On running the compiled .exe file, first the user will be asked to enter unique IP's of three routers(ranging from 16 to 255 only)
    
    -Then the program will create the network which will consist of 15 routers in top level connected in a ring(IP's-16,32,48....240,16)
     and there will be a similar ring connected to each router in lower level of network(for an IP i, lower ring will consist of IP's- i+1 to i+15 )
    
    -There user will be given a list of available options
    
    -If some data is requested, then it is converted into packets and the program will search for the shortest path from the user's IP to the IP where data is 
     stored
    
    -Program will also display the final path of the data packets by which they will reach user's router
    
    -In case if a router crashes from a path the program will find the next best path
    
    -If no path is possible "Server not found" will be shown
    
    -To check the functioning of program we can also crash any selected router and see the different paths chosen
