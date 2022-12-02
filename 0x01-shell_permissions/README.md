#!/bin/bash
su betty
-whoami
groups
chown betty /hello
touch hello
chmod 400 hello
chmod 744 hello
chmod 754 hello
chmod 555 hello
chmod 007 hello
chmod 753 hello
chmod --reference=olleh hello
#Command to execute permission to all subdirectories of the current directory for the owner, the group owner and all other users- chmod -R a-X .
#create directory with permission-mkdir -m 751 my_dir
-# command to change file user group- chgrp school hello
chmod -R a+X .
chmod a+X hello
chown vincent:staff *
