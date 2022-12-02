#!/bin/bash
su betty
-whoami
groups
chown betty /hello
touch hello
chmod 400 hello
