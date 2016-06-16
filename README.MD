windows local hosts file controller


** how to install **
This is a node module, to use this, you need to have nodejs installed on your machine.
Git clone this and go to the folder in your terminal then install using npm.
Install globally so the executable is accessible and usable.


	$ git clone https://wonsong82@bitbucket.org/wonsong82/localhost.git
	$ cd localhost
	$ npm install -g .

** how to use **
> to add hosts entry
$ localhost add -d $domainName -i $ipaddress
$ localhost add --domain domain.com -ip 192.168.10.10

> to remove hosts entry
$ localhost remove 

