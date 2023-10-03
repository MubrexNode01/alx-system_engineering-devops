My first Readme for shell redirections task. It states what each script does
#!/bin/bash 
"Hello, World"
This prints Hello, Worldto the screen
#!/bin/bash 
Õo
Te above script prints a conused smiley
#!/bin/bash 
cat /etc/passwd
The above script displays the contents of the file /etc/passwd
#!/bin/bash 
cat /etc/passwd /etc/hosts
#!/bin/bash 
tail -n 10 /etc/passwd
4. This prints the last 10 lines of the file /etc/passwd
#!/bin/bash 
head -n 10 /etc/passwd
5. The above script prints the first 10 lines of a/etc/passwd
#!/bin/bash 
head -3 iacta
6. The above script prints the 3rf line of a file
#!/bin/bash 
echo Best School > cat \*\Best School'\*$?*****:
7. This prints 'Best School' inside the file \*\'Best School\'\*$\?\*\*\*\*\*:) 
#!/bin/bash 
ls -la > ls_cwd_content
This redirects the output of ls -la to a file
#!/bin/bash 
rm *.js
10. The above script deletes all .js files
- #!/bin/bash \nls -n -al
11. This prints the lst of directories i long form including hidden 
#!/bin/bash 
tail -f -n 10 . 
12. This prints the new last 10 lines
#!/bin/bash 
file | sort | unique
This formats a file
#!/bin/bash 
grep root /etc/passwd
14. The abov script prints out a pttern "root" from a file
#!/bin/bash 
grep bin /etc/passwd | wc -l
#!/bin/bash 
grep root /etc/passwd | tail +3
16. The above script displays 3 lines after the pattern "root"
#!/bin/bash 
grep -v bin /etc/passwd
Diplays all the lines in the file that do not contain the pattern bin"
#!/bin/bash 
cat *[[:alpha:]] /etc/ssh/sshd_config
18. he above cript prints ou t all files startig with alphabet
#!/bin/bash 
A to Z | tr "A","c"  "Z","e
19. The above script one character with another
#!/bin/bash 
tr "c", "C" file
20. This scripts removes letters c and C from input
#!/bin/bash 
sort -R file
21. The above scripts reverses its input
#!/bin/bash 
ls -al /etc/passwd | sort -U
22. The above script sort displays all users sorted
#!/bon/bash 
ls -al| find -type -empty
23.The above script list all empty files
#!/bin/bash 
ls -al *.gif
24. The above script listall files with .gif extension
#!/bin/bash 
$ -ne 1 | ! -f $1 | $(line:01)
26. The above script parses web servers log as TSV files
15. he above scriptcunts number of times a patterrn appears in a file
#!/bin/bash 
parse_logs ilename | fmt | pr | lpr
