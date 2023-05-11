THIS FOLDER CONTAINS A SERIES OF SHELL SCRIPT AND THE FUNCTIONS THEY PERFORM

FILE 0-iam_betty:
This file is a script that switches the current user to the user betty.

FILE 1-who_am_i:
This script prints the effective username of the current user.

FILE 2-groups:
This file contains a script that prints all the groups the current user is part of.

FILE 3-new_owner:
This file is a script that changes the owner of the file hello to the user betty.

FILE 4-empty:
This script creates an empty file called hello.

FILE 5-execute:
This file contains a script that adds execute permission to the owner of the file hello.

FILE 6-multiple_permissions:
This file is a script  that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. The file hello will be in the working directory.

FILE 7-everybody:
This script adds execution permission to the owner, the group owner and the other users, to the file hello which is in the working directory without the use of commas.

FILE 8-James_Bond:
This scriptsets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
The file hello will be in the working directory You are not allowed to use commas.

FILE 9-John_Doe:
This script sets the mode of the file hello to this:
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
The file hello will be in the working directory, without using commas for this script

FILE 10-mirror_permissions:
This script sets the mode of the file hello the same as olleh’s mode.
The file hello will be in the working directory. The file olleh will be in the working directory.

FILE 11-directories_permissions:
This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

FILE 12-directory_permissions:
This script creates a directory called my_dir with permissions 751 in the working directory.

FILE 13-change_group:
This file contains a script that changes the group owner to school for the file hello. The file hello will be in the working directory.

FILE 100-change_owner_and_group:
This script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

FILE 101-symbolic_link_permissions:
This file contains a script that changes the owner and the group owner of _hello to vincent and staff respectively.
The file _hello is in the working directory. The file _hello is a symbolic link

FILE 102-if_only:
This script changes the owner of the file hello to betty only if it is owned by the user guillaume. The file hello will be in the working directory.

FILE 103-Star_Wars:
This script plays the StarWars IV episode in the terminal.




