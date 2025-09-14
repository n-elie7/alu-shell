## Permissions
This directory contains command about persmissions
## su command
This command is used to switch between different users.
## whoami command
This command is used to print the effective username of the current user
## groups command
This command is used to prints all the groups the current user is part of.
## chown command
This command is used to change owner of the file.
## touch command
This command is used to create a new file.
## chmod command 
This command is used to change permissions of file.
## chmod ug+x,o+r hello command
This command adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
## chmod ugo+x hello command
This is command  that adds execution permission to the owner, the group owner and the other users, to the file hello.
## chmod 007 hello command
This command set user and group with no permission and set others with all permissions in hello file.
## chmod 753 hello command
This command that sets the mode of the file hello to -rwxr-x-wx
## chmod --reference=olleh hello command
This command that sets the mode of the file hello the same as olleh’s mode.
## chmod a+X * command
This command add to all users execute permission, but only to directories.
## mkdir -m 751 my_dir command
This command create new directory and sets its permission to 751.
## chgrp school hello command
This command change the group owner to school for the file hello.
## chown vincent:staff *
This command that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
## chown -h vincent:staff _hello command
This command changes the owner to vincent and the group owner to staff for symbolic link _hello
## chown --from=guillaume vincent hello command
This command changes owner only if it is owned by guillaume
