
# Trax Emulator for Habbo Hotel v14
Welcome to the Trax Emulator project! This emulator is designed to replicate the Habbo Hotel v14 version.
Trax Emulator allows you, to create a habbo retro server from early habbo era.


HabboTrax emulator is not for an production hotel yet.






## Features

- lightweight Emulator
- Cross Plataform (Windows/MacOS/Linux)
- Habbo registration/login



how to install the habbo dcrs:

- install a webserver (xampp, etc) and copy the index.php & Habbo v14 folder.

- if you are using VPS - (Edit index.php and change localhost from your server IP)

- if you are using VPS - (go to v14 folder, and edit external_variables.txt and index.php amnd change localhost for your server IP)

- Now you will go to localhost to see the webserver active.
```bash

```
To import database
- install mariadb (windows & linux)
- connect into your mariadb account, and import the database.
```bash

```


## How deploy Trax Emulator

To run the emulator:

```bash
  - Open game_server.py and game_client.py  with your IDE and change "127.0.0.1" to your VPS IP and Habbo Client port.
- 
- Now execute the game_server.py and game_client.py with python3 <game_server.py> python3 <game_client.py> 

```




## Acknowledgements

 - [Quackster ](https://github.com/Quackster) - for client, dcrs & Database
 - [ironicc](https://github.com/Criminalz0x) - Developing Emulator

## Authors

- [ironicc](https://github.com/Criminalz0x) - main developer

