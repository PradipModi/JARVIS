//-----------------------------------------------------------------------------------------------
//J.A.R.V.I.S. Version 1
//PHP MYSQLI AIML interpreter
//Written by Pradip Mudi
//January 2017
//-----------------------------------------------------------------------------------------------



To install for the first time
----------------------------------------
*upload files to a server with php/mysql
*open the file install_programo.php and follow the instructions




To upgrade an existing version
----------------------------------------
*back up your old files
*overwrite the existing files with new ones
*do not run the installers as this will wipe the existing bot tables
*please look at ./index.php and bot/chat.php to see how the html has 
	been removed from chat.php (v1.0.3) the simplest way to update your bot 
	is to remove the php code from the page which contains the html form
	and include("bot/chat.php") in this original page.  