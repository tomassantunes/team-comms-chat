# team-comms-chat
Final uni project for Networks

## **Usage**:
To initiate the server, open a terminal in the project directory and execute the following command:
```bash
gcc -o server server.c
./server
```

In a new terminal or tab, to execute a client execute the following command:
```bash
gcc -o client client.c
./client <hostname> <port number>
```
*Default port is 1234.*

To define your nickname use:
```
HELLO <nickname>
```

To subscribe to a team/group:
```
SUB <team-name>
```

Available teams/groups by default:
- ADMIN
- MEMETEAM
- BESTTEAM
- CHEATERSTEAM

Global message:
```
MSG GLOBAL <message>
```

Message to user:
```
MSG USER <nickname> <message>
```

Message to team/group:
```
MSG <team-name> <message>
```

Post messages (only available for the GLOBAL channel):
```
POST GLOBAL <message>
```

Read the posts available:
```
READ GLOBAL
```

Transfer files:
```
FILE USER <nickname> <filename> <bytes>
```

- Authors:
  - [Tomás Antunes](https://github.com/tomassantunes)
  - [Daniel Barreiros](https://github.com/dbarreiros)