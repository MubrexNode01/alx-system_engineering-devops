this documentation explains what each script does

#!/bin/bash
su betty : switches user to betty
#!/bin/bash
id -u : prints effective user id
#!/bin/bash
id -G : prints al groups a user belongs 
#!/bin/bash
chown betty hello : change owner of the file hello to betty
#!/bin/bash
touch hello : creates an empty file called hello
#!/bin/bash
chmod u+x hello : adds execution permissions to owner
#!/bin/bash
chmod ug+x, o+r hello : gives execution permissions to owner and group owner, write permissions ro others
#!/bin/bash
chmod ugo+x hello : adds execution permissions to owner, group and others
#!/bin/bash
chmod 007 hello :gives other all permissons and removs all permissions foe owner and group owner
#!/bin/bash
chmod 753 hello : adds all permission to owner, read and write to group owner and write and execute to others for the file  hello 
#!/bin/bash
umask 0002  sets the permission of a file to remove write access 
#!/bin/bash
chmod -R ugo+x . :adds execution permissions to owner, group owner and others
#!/bin/bash
chmod -d 751 my_dir : changes mode of directory my_directory 
#!/bin/bash
chgrp school hello : changes the group owner of file  to school
#!/bin/bash
chown vincent : staff hello : changes owner and group owner of the file hello
#!/bin/bash
chown -R vincent : staff . : changes ownership of all directories and sub-directories in the current working directory
#!/bin/bash
chown -ln vincent : staff _hello : changes owner and group owner of a symbolic link
#!/bin/bash
chown betty hello if %U "hello" == guillaume : changes file ownership to betty if and only if the file is own by guillaume
#!/bin/bash
telnet towel.blinkenlights.nl : watch star wars in the terminal
