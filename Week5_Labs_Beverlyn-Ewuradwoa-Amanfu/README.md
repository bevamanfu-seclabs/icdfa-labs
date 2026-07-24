Name: Beverlyn Ewuradwoa Amanfu
Registration Number: C11/26/FCDF/17155 

## Reflection 
In lab 22 - 24, I learnt about the different shell types. One thing that I found interesting is that the different shell types have different names for their configuration files. My shell type is Z shell and its configuration file is .zshrc. I also learnt that the config is personalizable in the sense that I can permanently alter the config file to include aliases for commands I usually use.
File manipulation skills were re-inforced during this lab and I was introduced to file globbing. 

## Challenge
I encountered a challenge when running the command "ls file[!3].txt". Instead of the output being file1.txt and file2.txt, !3 in the command was replaced with sudo passwd root. From research, I found that this occured because of a feature called History Expansion, so instead of the command being executed as ' not file3.txt' it was returning the third command I typed in the terminal session.  To fix this, I had to modify the command, using ^ or \! for negation instead of !. 


## Key commands used 
alias  - creates a shortcut for a longer command. This is temporary
nano ~/.zshrc - opens the configuration file for Z shell
source ~/.zshrc - reloads the config file without restarting the terminal. The command reads the new additions to the config file.
'*' - matches 0 or more characters
ls *.txt - lists all files with the extension txt
ls file* - lists all files whose name starts with "file"
'?' - matches exactly one character
ls file?.txt - lists all files with the extension txt, whose name starts with "file", then one character.
'[]' - matches any single character inside the brackets
ls file[12].txt - lists file1.txt and file2.txt