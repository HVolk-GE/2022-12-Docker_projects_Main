# Docker-Webserver-Image:

Following Packages are included:
(Editable with the Versions inside the .env and inside the webserver\Dockerfile )
		Debian bullseye-slim,
		PHP 8.1-fpm-alpine,
		apache2,
		MySQL(MariaDB-latest),
		(Optional):
		Deactive CouchDB with comment out (with # character on start position at all lines),
		Or delete all lines after #---------------------- line !
		CouchDB3.

# Environment

1.) Needed Install Software:
		Docker (optional Docker-Desktop),
2.) Execute all Operation Systems:
		Linux,
		MaxOS,
		Windows.

3.) Installation:
		Create new folder with your own "Project-Name" eg. D:\myProjects\FirstProject 
		or for Frameworks:
		Create new Project - Foldername like Project-Name, afterwards copy following folders in the Project folder:
		
		a.) For using only MySQL follows Folder: 
			"data" with all subfolders are exists
			Side Notes; it's possible you have to change the .env File for User access.
		
		b.) For using Webserver includes PHP and MySQL:
			Copy Folders from 3.a and webserver Folder with all Files
			and code Folder with all Subfolder and Files.

		c.) If you create the first time and you need to create a Docker Image with all Containers:
		Copy "all Files and Folders" from this Zip-Package into this Folder.
		Inside your Project Folder, execute following command in the shell (CMD/Terminal):

		docker-compose up -d

		Docker will install all missing files and dependencies, when Docker can't find on your System.

4.) Your Project-Files: 
		Should be saved/create inside ./code/public/ Folder

# Start commando:

		docker-compose up -d
		or start the needed Container(s) with Docker-Desktop or shell command to start needed Container(s).

