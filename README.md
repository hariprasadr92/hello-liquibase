# hello-liquibase
Exploring Liquibase. Kind of a VCS for Database Changes

This project is just a simple wire frame for starting liquibase to be set up with your database. 
Refer to "liquibase_notes" for more info on how to use liquibase.

# Installation steps 

## Download .exe file

- run the exe file it set the path automatically and creates the root folder



## or get the .zip folder

Make sure 
- 	Java 8 or above is installed. 
- 	JAVA_HOME is set properly 
-	Extract the contents into some location (this is your liquibase roor folder)
-  	Set path if you are in a windows machine (to the extracted location )
	For ex. C:\liquibase-3.8.9
	
From cmd or powershell , do a'liquibase' command from any directory to check if installtion is successful.

# Info about the repo

* 'liquibase.properties' - contains the config details needed for your setup. 

* 'myChangeLog.xml' - this wil contains the liquibase code / logic that you wanna write. 

# Getting started with liquibase

After liquibase installtion and setting up your repo. Just do a 'liquibase update' command and the DB file ( .mv.db) will get created. 

Refer to "liquibase_notes" for more info on how to use liquibase. Thank me later.

Now the ball is in your court.
'Enjoy ! Explore ! Cheers !'
