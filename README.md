 <h1> A collection of scripts written for use in the game grey hack https://store.steampowered.com/app/605230/Grey_Hack/ </h1>
<br>
<small> WIP </small><br>

<b> Acknowledgments </b><br>
// Thank you @github: WyattSL for the GreyHack Game documentation<br>
// Thank you @github: psimonson for https://github.com/psimonson/greyhack-scripts/tree/master/v0.8/scripts<br>
<br>
## INSTALL ##

-- create a folder named src, and place all scripts inside of it via the game code editor

-- adjust the paths for the refernce code in main.src and autolocal.src <br>
ex: import_code("/home/USER/src/utils.src")

-- You will need to compile the following files in this order, name the binary the same as the src<br><br>
1.) shellobj.src --> ** MUST ALLOW IMPORTS ** <br>
2.) compobj.src --> ** MUST ALLOW IMPORTS **<br>
3.) fileobj.src --> ** MUST ALLOW IMPORTS **<br>
4.) binary.src --> ** MUST ALLOW IMPORTS ** --> SENSITIVE FILE, DELETE THE SRC<br>
5.) send.src --> ** MUST ALLOW IMPORTS ** --> SENSITIVE FILE, DELETE THE SRC<br>
6.) eel.src --> SENSITIVE FILE, DELETE THE SRC<br>
7.) payload.src <br>
8.) main.src --> RENAME TO ss 

eel.src --> rshell payload, must define your rshell's IP <br>
binary.src --> contains obfuscated variables for root, users, and your FTP depot server info <br> 
send.src --> references binary.src, for your protection, do not keep src as these can be easily compromised<br>



Once complete, the only required filed are ss, eel, and payload<br>
Hope you enjoy if you find useful;<br>
![image](https://github.com/Tuna-Terps/grey-hack-game-scripts/assets/62733984/0ac8a1f3-e4e1-4c42-8c60-8d3d429b74a2)
<br>
<h1>Some commands available in surf mode/h1><br>
![image](https://github.com/Tuna-Terps/grey-hack-game-scripts/assets/62733984/544b0be0-0532-4e5b-9cf3-cd3bb4cf7b0b)

 ![image](https://github.com/Tuna-Terps/grey-hack-game-scripts/assets/62733984/5cda8245-88db-447b-9bd2-257a7f247a34)

<h3>global objects <br> </h3>
![image](https://github.com/Tuna-Terps/grey-hack-game-scripts/assets/62733984/244a98e5-bd64-4911-9383-a8cd5578e942)
