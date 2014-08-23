#conServers.sh#

##Intro##

This is script list all server from html page with table (<td>) and automatc coonect  in selected server.

##Requirements##

1. Linux or MacOSX
2. Ruby with bundle (gem install bundle)
2. SSH RSA Key to connect on Server
3. HTML Page with table (Company | Hostname or ip Address| user| port | alias )
	
##How to Install##
	cd ~/
	wget https://github.com/brfso/conServers/archive/master.zip
	unzip conServers-master.zip
	cd $PWD/conServers-master/
	./install.sh

Notes: Mac Users can install wget using this is how to: http://osxdaily.com/2012/05/22/install-wget-mac-os-x/
	
##How to Use##

	1. Set SSH Key in SSH_KEY in /etc/conservers.config
	2. Change Page to connect (url) in /etc/conservers.config
	3. Execute conServers.sh
		conservers.sh
		
####To Update Server List	
	To update server list from html page, execute with option -a:
	conserver.sh -a

##toDO##
To view or make one request use: https://github.com/brfso/conServers/issues

