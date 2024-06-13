In this directory I will be going through tasks related to shell-permissions.
The functions of all scripts in the different files are listed below:
    *0-iam_betty ; This script switches to current user to the user 'betty'
    *1-who_am_i ; This script prints the effective username of the current user
    *2-groups ; This script prints all the groups the current user is part of
    *3-new_owner ; This script changes the owner of the file 'hello' to the user 'betty'
    *4-empty ; This script creates an empty file 'hello'
    *5-execute ; This script add execute permission to the owner of the file 'hello'
    *6-multiple_permissions ; This script adds execute permisson to the owner and the group owner, and read permisson to other users, to the file 'hello'
    *7-everybody ; This script adds execution permission to the owner, the group owner, and other users, to the file 'hello'
    *8-James_Bond ; This script gives no permission at all to the owner and the group owner but gives all permissions to other users
    *9-John_Doe ; This script gives the owner all permissons, the group owner only read and execute permissions and write and execute permissons to other users
    *10-mirror_permissions ; This script sets the mode of the file 'hello' to always be the same as the mode of the file 'olleh' even if it is changed
    *11-directories_permissons ; This script adds execute permission to all sub-directories of the current directory for the owner, the group owner and all other users
    *12-directory_permissons ; This script creates a directory called 'my_dir' with all permissions to the owner, read and execute permissions to the group owner and only read permissions to other users, in the working directory
    *13-change_group ; This script changes the group owner to 'school' for the file 'hello'
    