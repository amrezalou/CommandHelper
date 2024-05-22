* ``` date ``` displays the current time and date.

* ``` df ``` to see the free space on the disk drives.

* ``` pwd ``` prints the name of current working directory.

* ``` cd ``` change the directory.
* ``` cd - ``` changing into previous directory.
 
* ``` ls ``` listing content of working directory.
* ``` ls -ltrh ``` flags using for display more information and human readable like permissions.

* ``` file ``` indicate file type.

* ``` less ``` view file contents. -> G: move to end - q: quit less.

* ``` cp ``` copy files and also directories.
* ``` cp -r dir1 dir2 ``` if dir2 not exist it will create it. 

* ``` mv ``` move or rename files or directories.
* ``` mv dir1 dir2 ``` if dir2 not exist, it will change dir1 name to dir2.

* ``` rm ``` removing files.
* ``` rm -d ``` removing directory.
* ``` rm -rf ``` is also uses for forcing and deleting directory.
 
* ``` ln ```  creating hard and symbolic links.
* ``` ln -s item link ``` creating a link of 'link', item can be either a file or directory.

* ``` mkdir ``` creating directories.
* ``` rmdir ``` deleting directories.

* ``` type ``` indicates how a command name is interpreted.

* ``` which ``` display which executable program will be executed.

* ``` help ``` getting help.

* ``` man ``` display manual page of commands.
* point of linux's power is that you can use all commands manual pages by this command.

* ``` apropos ``` to see list of appropriate commands.

* ``` info ``` display commands info.
 
* ``` whatis ``` display one-line description of command.

* ``` alias ``` creat an alias for a command.  
* e.g: ``` alias run='g++ main.cpp -o main && ./main' ``` -> using for compile and run a .cpp file.
* ``` unalais ``` for unalias an alias.
* notice that you should save your alais in bashrc file -> ``` nano ~/.bashrc ```. 