A3Wasteland Chernarus by Motavar
====================

VIDEO GAME: Arma 3<br>
MISSION: Ethix Gaming's A3Wasteland Altis<br>
GAME TYPE: Survival / Conquest warfare<br>
<br>
AUTHOR: TaycoMan <br>
EMAIL: tacomann199@gmail.com<br>
<br>
Server Admins or Windows 2008 R2 Users Please Note: 
If you receive an error that you could not load Ragnar.dll you are required to install Visual Studio 2013 C++ Redistributable (32 bit). You will need to load the 32-bit files onto your x64 bit OS. The 64bit files do not contain the 32bit files required by the application when running in WOW mode.<br>
<br>
<b>WINDOWS INSTALLATION:</b><br>
<br>
<b>DATABASE SETUP:</b><br>
install mysql<br>
copy "a3wasteland_db_v2.03.sql" to your mysql bin directory (where your mysql.exe is located)<br>
example: C:\Program Files (x86)\MySQL\MySQL Server 5.6\bin<br>
login to mysql<br>
<br>
example:<br>
>><br>
C:\>cd "Program Files (x86)<br>
C:\Program Files (x86)>cd MySQL<br>
C:\Program Files (x86)\MySQL>cd MySQL Server 5.6<br>
C:\Program Files (x86)\MySQL\MySQL Server 5.6>cd bin<br>
C:\Program Files (x86)\MySQL\MySQL Server 5.6\bin>mysql -u root -p<br>
Enter password: your database password<br>
<br>
Create the database:<br>
mysql> source a3wasteland_db_v2.03.sql<br>
exit out<br>
<<<br>
<br>
<br>
<b>A3WASTELAND SETTINGS SETUP:</b><br>
Copy the "A3Wasteland_settings" directory to the Arma directory (where you have your arma3.exe)<br>
This contains the mission settings stored in the "main_config.sqf"<br>
<br>
<br>
<b>INSTALL extDB2</b><br>
open extDB2-v55.rar file, go into the windows folder and extract the files to the Arma3 directory (where you have your arma3.exe)<br>
Switch over to your Arma 3 directory<br>
Go into the @extDB2 directory and edit extdb-config.ini file<br>
configure your passwords <br>
<br>
Change the following:<br>
Version = 3<br>
to<br>
Version = 4<br>
<br>
find the following<br>
>><br>
[MySQL_Example]<br>
Type = MySQL<br>
Name = Database_Name<br>
<br>
Username = root<br>
Password = password<br>
<<<br>
Change to:<br>
[A3W]<br>
Type = MySQL<br>
Name = a3wasteland<br>
Username = root<br>
Password = whatever your pw is for db<br>
<br>
save the file and exit<br>
<br>
<br>
<b>SQL CUSTOM FOLDER SETUP:</b><br>
Copy the "sql_custom" directory to your Arma 3 @extDB2/extDB/ folder. Overwrite the folder that is in there<br>
<br>
<br>
<br>SERVER EXE SETUP:</b><br>
<br>
<br>
Ethix Gaming's A3Wasteland Settings Directory (changes for player HUD):
In your A3wasteland settings directory add the following to your main_config.sqf<br>
// Server Naming<br>
A3W_serverName = "Your Server Name";	//Name of your server for Player HUD<br>
A3W_serverIP = "127.0.0.1";		       //IP address of your server for Player HUD<br>
A3W_serverWWW = "www.your_web_site.com";	//Server HTTP address<br>
<br>
<br>
*SERVER ADMINS - WARNING NOTE:<br>
Ethix Gaming's A3Wasteland  does not support "Samatra Wasteland Chernarus" versions of RHS/HLC/AIA/JR mods as they are not signed by the original authors.<br>
Take warning if you are using their files for the mission type, your server is subject to compromise using unsigned files. 
<br>
<br>
CREDITS: <br>
<br>
Core by A3Wasteland.com<br>
Code Modified by TOPARMA.COM<br>
Chernarus port by TAC-X.com<br>
Help and suggestions from many members of the open Arma community.<br>
<br>
<br>
