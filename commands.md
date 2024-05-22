* ``` date ``` displays the current time and date.
___
* ``` df ``` to see the free space on the disk drives.
___
* ``` pwd ``` prints the name of current working directory.
___
* ``` cd ``` change the directory.
* ``` cd - ``` changing into previous directory.
___
* ``` ls ``` listing content of working directory.
* ``` ls -ltrh ``` flags using for display more information and human readable like permissions.
___
* ``` file ``` indicate file type.
___
* ``` less ``` view file contents. -> G: move to end - q: quit less.
___
* ``` cp ``` copy files and also directories.
* ``` cp -r dir1 dir2 ``` if dir2 not exist it will create it. 
___
* ``` mv ``` move or rename files or directories.
* ``` mv dir1 dir2 ``` if dir2 not exist, it will change dir1 name to dir2.
___
* ``` rm ``` removing files.
* ``` rm -d ``` removing directory.
* ``` rm -rf ``` is also uses for forcing and deleting directory.
___
* ``` ln ```  creating hard and symbolic links.
* ``` ln -s item link ``` creating a link of 'link', item can be either a file or directory.
___
* ``` mkdir ``` creating directories.
* ``` rmdir ``` deleting directories.
___
* ``` type ``` indicates how a command name is interpreted.
___
* ``` which ``` display which executable program will be executed.
___
* ``` help ``` getting help.
___
* ``` man ``` display manual page of commands.
* point of linux's power is that you can use all commands manual pages by this command.
___
* ``` apropos ``` to see list of appropriate commands.
___
* ``` info ``` display commands info.
___
* ``` whatis ``` display one-line description of command.
___
* ``` alias ``` creat an alias for a command.  
* e.g: ``` alias run='g++ main.cpp -o main && ./main' ``` -> using for compile and run a .cpp file.
* ``` unalais ``` for unalias an alias.
* notice that you should save your alais in bashrc file -> ``` nano ~/.bashrc ```. 
___