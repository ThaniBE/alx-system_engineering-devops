#!/bin/bash

# Script 0-iambetty

-- Switch the current user to the user betty

# Script 1-whoAmI

-- Print the effective username of the current user

# Script 2-groups

--Print all the groups the current user is in

# Script 3-newOwner

-- Change the owner of file hello to user betty

# Script 4-empty

-- Create an empty file called hello

# Script 5-execute

-- Add execute permission to the owner of file hello

# Script 6-multiplePermissions

-- Add execute permission to the owner and the group owner, and read permission to other users, too the file hello

# Script 7-everybody

-- Add execute permission to the owner, group owner and other users to the file hello

# Script 8-JamesBond

-- Set permission to file hello such that owner and group owner have no permissions at all  while other users have all permissions

# Script 9-JohnDoe

-- Set mode of file hello to -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

# Script 10-mirrorPermissions

-- Set mode of file hello to be same as olleh

# Script 11-directoriesPermissions

-- Add execute permissionto all subdirectories in the current directory of the owner, group owner and all other users. Regular files should remain unchanged

# Script 12-directoryPermissions

-- Create a directory called my_dir with permission 751 in the current directory

# Script 13-change_group

-- Change the group owner to school for the file hello

