#!/bin/bash
su betty
-whoami
groups
chown betty /hello
touch hello
chmod 400 hello
chmod 744 hello
chmod 754 hello
chmod 751 hello
