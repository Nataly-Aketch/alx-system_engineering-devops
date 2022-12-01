

### Shell permissions

This project contains executable shell scripts for shell permissions including command such as chmod, chown, whoami etc

Initially appeared on:

https://github.com/Nataly-Aketch/alx-system_engineering-devops/tags

## Getting started

These instructions give you a copy of the project

### Prerequisites

Requirements for running this project is Ubuntu 20.4 LTS

###Scripts

#Switches current user to betty

#!/bin/bash

su betty

#Prints username of current user

#!/bin/bash

whoami

#Prints all groups currents user is part of

#!/bin/bash

groups

#Changes owner of the file ‘hello’ to user betty

#!/bin/bash

chown betty hello

#Creates an empty file called hello

#!/bin/bash

touch

#Adds execute permission to owner of file ‘hello’

#!/bin/bash

chmod 744 hello

#Adds execution permission to owner, group owner and other users for file ‘hello’

#!/bin/bash

a+x hello

#Sets the permission to the file hello of owner to no permission at all, group to no permission at all other users to all the permissions

#!/bin/bash

chmod 007 hello

#Sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

 #!/bin/bash

Chmod 753 hello

##Authors

Nataly-Aketch

https://github.com/Nataly-Aketch






