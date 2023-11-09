# Chat-Application
A chat room application that is made in C++. Supports chatting among multiple clients.

## How to run?
1. __Clone__ or __Download__ this respository.
2. Run these following commands in the terminal.
```json
g++ server.cpp -lpthread -o server
g++ client.cpp -lpthread -o client
```
3. To run the __server__, type this command in the terminal;
```json
./server
```
4. Open another terminal and type this command in the terminal and run the client;
```json
./client
```
5. To have multiple clients, just repeat the step in __STEP 4__
