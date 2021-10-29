# irc_files_executable



CLIENT COMMANDS:

/addRoom: adds one room to the server
/joinRoom 'X' 'Y' 'Z' '...': allows client join one or more rooms
/listAllRooms: returns the number of rooms within the server
/leaveRoom 'X' 'Y' 'Z' '...': allows client leave one or more rooms
/all 'string': allows message to be sent to every room in sever
/writeTo 'X' 'Y' 'Z' '...' 'string': (no spaces between numbers) sends message to specified rooms
/listAllClients: lists all the clients in every room

Not specifying a command will default to a message sent to room 0.


SERVER COMMANDS:

/listAllClients: lists all the clients in every room


