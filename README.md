# Sendy-Exclude-Lists-Feature
Currently works only with Sendy 2.1.2.8

Instructions:

* Back up your files and database just in case.
* Download zip file from https://github.com/iburban/Sendy-Exclude-Lists-Feature/archive/master.zip
* Unzip and upload its contents to your Sendy installation using an FTP client (like FileZilla) overwriting Sendy files.
* Go to url http://your-sendy-installation.com/exclude-db-changes.php Put your own Sendy url of course. This will make a necessary change to your database (it adds a column 'exlclude_lists' to 'campaigns' table; completely safe).
* Delete exclude-db-changes.php file from your server.

That should be it. Now when you create a new campaign you'll have an option to select which lists you'd like to exclude.

**Stay Updated!**

If you want to get a message when I update this mod for a new Sendy version,
subscribe here (this is a list for updates only):

=> http://www.pluginsbyigor.com/sendy-mod-updates

Cheers,

Igor
 
