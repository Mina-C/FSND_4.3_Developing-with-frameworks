# FSND_4.3_Developing-with-frameworks
This is learning by coding for Full Stack Web Developer Nanodegree Program - 4. Servers, Authorization, and CRUD - 3. Developing with Frameworks. 
This journey creates a web site using framework called Flask.

## How to run
You need Python(ver.3), Linux-based virtual machine environment(Vagrant and VirtualBox).
  1. To make the virtual machine(VM) online, use the commands "vagrant up". Then log on it with "vagrant ssh".</br>
    To download Vagrant : https://www.vagrantup.com/downloads.html </br>
    To download VirtualBox : https://www.virtualbox.org/wiki/Downloads
  2. Please download "lotsofmenus.py", "database_setup.py", "project.py" "Vagrantfile". Then put this file into a shared directory.</br>
    Download "database_setup.py", "Vagrantfile" <a href='https://github.com/Mina-C/FSND_4.2_Making_Web_Server'>here</a> </br>
	  Download "lotsofmenus.py" here - https://github.com/lobrown/Full-Stack-Foundations/blob/master/Lesson_1/lotsofmenus.py </br>
	  How to make shared directory? - https://www.howtogeek.com/189974/how-to-share-your-computers-files-with-a-virtual-machine/
  3. To make the database, "cd" into the shared directory and use the command "python lotsofmenus.py". Then, "restaurantmenu.db" file will be created.</br>
  4. Please run the code with "python project.py". And to stop the server, please press Ctrl+C.
  5. Open the browser and type the address: http://localhost:5000/.
  
