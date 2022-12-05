

### Shell I/O redirections

This project contains executable shell scripts for shell I/O redirections including command such as tr, grep, tail, cat, echo, uniq and sort among others

Initially appeared on:

https://github.com/Nataly-Aketch/alx-system_engineering-devops/tags

## Getting started

These instructions give you a copy of the project

### Prerequisites

Requirements for running this project is Ubuntu 20.4 LTS

###Scripts

#Prints “Hello, World”

#!/bin/bash

echo “Hello, World”

#Displays a confused smiley

#!/bin/bash

echo “\”()’”

#Displays contents of /etc/passwd

#!/bin/bash

cat /etc/passwd

# Displays contents of /etc/passwd and /etc/hosts

#!/bin/bash

cat /etc/passwd /etc/hosts

#Displays last lines of /etc/passwd

#!/bin/bash

cat /etc/passwd | tail

#Displays first lines of /etc/passwd

#!/bin/bash

cat /etc/passwd | head

#Displays 3rd line of the file iacta

#!/bin/bash

head -3 iacta | tail +3

#Duplicates last lines of the file iacta

#!/bin/bash

tail -n 1 ./iacta >>iacta

#Counts number of directories and subdirectories

 #!/bin/bash

Ls -lR | grep ^ |wc -l

##Authors

Nataly-Aketch

https://github.com/Nataly-Aketch






