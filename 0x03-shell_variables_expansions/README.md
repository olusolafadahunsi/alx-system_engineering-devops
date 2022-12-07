#!/bin/bash
alias ls="rm *"
echo "hello $USER"
export PATH="$PATH:/action"
echo $PATH | tr -s ":" "\n"| wc -l
env
set
