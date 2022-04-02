# Chat-Client-Server
Created a C++ program using select() and multithreading

### Run Program
- g++ -pthread client.cpp RobustIO.cpp -o client && g++ server.cpp RobustIO.cpp -o server
- Run ./server on one terminal 
- Run ./client on the other terminal 
- Can connect multiple clients 
- Send chat log history to new clients that join
