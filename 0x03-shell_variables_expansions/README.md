#!/bin/bash
echo "hello $USER"
export PATH="$PATH:/action"
echo $PATH | tr -s ":" "\n"| wc -l
set
