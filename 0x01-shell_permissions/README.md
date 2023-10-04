0x01-shell_permissions
This project contains Bash scripts that focus on file permissions in Linux. Each script performs specific tasks related to changing permissions, ownership, and group ownership of files and directories.

Scripts
0-iam_betty

Switches the current user to the user "betty."
1-who_am_i

Prints the effective username of the current user.
2-groups

Prints all the groups the current user is a part of.
3-new_owner

Changes the owner of the file "hello" to the user "betty."
4-empty

Creates an empty file called "hello."
5-execute

Adds execute permission to the owner of the file "hello."
6-multiple_permissions

Adds execute permission to the owner and group owner, and read permission to other users for the file "hello."
7-everybody

Adds execution permission to the owner, group owner, and other users for the file "hello."
8-James_Bond

Sets the permission of the file "hello" as follows: Owner - no permission, Group - no permission, Other users - all permissions.
9-John_Doe

Sets the mode of the file "hello" to -rwxr-x-wx.
10-mirror_permissions

Sets the mode of the file "hello" to match the mode of the file "olleh."
11-directories_permissions

Adds execute permission to all subdirectories of the current directory for the owner, group owner, and all other users. Regular files are not changed.
12-directory_permissions

Creates a directory called "my_dir" with permissions 751 in the working directory.
13-change_group

Changes the group owner of the file "hello" to "school."
Usage
Make sure the scripts are executable before running them. You can use the chmod command to make them executable:

bash
Copy code
chmod +x script_name
To run a script, simply execute it:

bash
Copy code
./script_name
Replace script_name with the name of the script you want to run.

Feel free to explore and use these scripts to learn more about Linux file permissions0x01-shell_permissions
This project contains Bash scripts that focus on file permissions in Linux. Each script performs specific tasks related to changing permissions, ownership, and group ownership of files and directories.

Scripts
0-iam_betty

Switches the current user to the user "betty."
1-who_am_i

Prints the effective username of the current user.
2-groups

Prints all the groups the current user is a part of.
3-new_owner

Changes the owner of the file "hello" to the user "betty."
4-empty

Creates an empty file called "hello."
5-execute

Adds execute permission to the owner of the file "hello."
6-multiple_permissions

Adds execute permission to the owner and group owner, and read permission to other users for the file "hello."
7-everybody

Adds execution permission to the owner, group owner, and other users for the file "hello."
8-James_Bond

Sets the permission of the file "hello" as follows: Owner - no permission, Group - no permission, Other users - all permissions.
9-John_Doe

Sets the mode of the file "hello" to -rwxr-x-wx.
10-mirror_permissions

Sets the mode of the file "hello" to match the mode of the file "olleh."
11-directories_permissions

Adds execute permission to all subdirectories of the current directory for the owner, group owner, and all other users. Regular files are not changed.
12-directory_permissions

Creates a directory called "my_dir" with permissions 751 in the working directory.
13-change_group

Changes the group owner of the file "hello" to "school."
Usage
Make sure the scripts are executable before running them. You can use the chmod command to make them executable:

bash
Copy code
chmod +x script_name
To run a script, simply execute it:

bash
Copy code
./script_name
Replace script_name with the name of the script you want to run.

Feel free to explore and use these scripts to learn more about Linux file permissions.
.
