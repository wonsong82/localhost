windows local hosts file controller


** how to install **

This is a node module, to use this, you need to have nodejs installed on your machine.
Git clone this and go to the folder in your terminal then install using npm.
Install globally so the executable is accessible and usable.


	$ git clone https://wonsong82@bitbucket.org/wonsong82/localhost.git
	$ cd localhost
	$ npm install -g .


** how to use **


```
#!shell

Usage: localhost [command] {Options}


    no command  Toggle enable / disable

          list  Show the list of the sites defined in hosts file

        enable  Enable local hosts

       disable  Disable local hosts

        status  Show the status whether the local env is enabled / disabled

           add  Add to hosts file
                --domain, -d  Domain of the host, required
                    --ip, -i  Local ip of the entry, omitting defaults to 127.0.0.1

        remove  Remove from hosts file
                --domain, -d  Domain of the host, required

     --help, h  Show this message


```