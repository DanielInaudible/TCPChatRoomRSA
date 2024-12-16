## TO-DO
- Research possible implementations of TCP server for hnadling multiple clients, as for this time's knowledge, i can only think of handling 1 client for a given socket a server has, possible explanation: https://www.geeksforgeeks.org/socket-programming-in-cc-handling-multiple-clients-on-server-without-multi-threading/

- Decide whatever to use / not use NCURSES for UI(probably not)
- When this is done, start thingking of RSA key exchange (diffie helman). I know how it works, what it does, so i will just need to handle cases, for when a new host joins the chatroom. Will the chatroom store the keys so in the chatroom there will be encryption/decryption, or should i store all other user keys on endpoints such as clients ?(investigate later)