This dir 0x01-shell_permissions conatins an executable files of all the permissions scripts:

The 0-iam_betyy file contains the scrip that switches from the current user to another user nammed betty

The 1-who_am_i file contains The script that allows to print the effective username of the current user

The 2-groups file contains a script that prints all the groups the current user is part of

The 3-new_owner file contains the script inside allows to change the owner file hello to the user betty

The 4-empty file contains the script that creates an empty file called hello

The 5-execute file contains the script that adds an execute permession to the owner of the file

The 6-mutiple_execute is a file contains the script that allows to change permessions to files; including read (r), write (w) and execute (x) permessions for owner (u), group owner (g) and other users (o)

The 7-everybody file contains the script that adds execution permission to owner, group owner and other users

The 8-James_Bond file contains the script that gives full permission to others user and takes all permissions from Owner and group to the file hello

The 9-John_Doe file contains the script that sets the mode of the hello file, hello file is in the working dir

The 10-mirror_permissions file contains the script sets the mode of file hello the same as olleh's mode

The 11-directories_permissions file contains the script that adds execute (x) permession to all subdirectories of the current dir for all users (owner, group and others).

The 12-directory_permissions contains a script that creates a directory named my_dir with permissions 751 in the working dir

The 13-change_group file contains the script that changes the group owner to school for the file hello

The 100-change_owner_and_group file conaints the command chown uses to change the owner and group owner for all files and directories in the current working directory (.). The -R option makes the operation recursive

The 101-symbolic_link_permissions file contains the script that allows to change the owner and the group owner of a symbolic link in your dir

The 102-if_only file contains the script that changes the current owner of a file only if it mathches the current owner of the specific file; in our case, the script changes the owner of hello file to betty only if it matches guillaume as the name if the current owner of the file

The 103-Stars_Wars file contains script using telnet protocol to desplay the SatrWars IV in the terminal once the script is running
