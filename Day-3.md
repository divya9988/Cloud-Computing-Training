Day 3 - Task 2 (Directory Structure and Permissions)
Date: 02/07/2026

# Completed the following activities:

1.Created directory hierarchy under /company.

2.Created /company/developers.

3.Created /company/testers.

4.Created /company/backups.

5.Assigned ownership and group permissions.

6.Allowed developers to access only the developers directory.

7.Allowed testers to access only the testers directory.

8.Restricted unauthorized users from accessing protected directories.

9.Configured backup directory access for the administrator.

## Commands practiced:

sudo mkdir -p/company/{developers,testers,backups} -> create directary structure
sudo chown -> create  owernership of group
sudo chgrp developers /company/developers   ->  assign groups
sudo chmod 777 /company/developers          ->  set passwords
ls -ld /company/*                           ->  verify
  
