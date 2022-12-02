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
