# OWS-visualize
A JS webpage for visualizing data pulled from a specific file.
Setup:
	- Update and upgrade system: `sudo apt-get update` then `sudo apt-get upgrade`
	- Update remote `curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -`
	- install nodejs with `sudo apt-get install nodejs`
	- install build essentials with `sudo apt-get install -y build-essential`
	- Install Nginx using package manager: `sudo apt-get install nginx`
	- Replace the nginx config (located in `/etc/nginx/`) with the custom one provided.
	- Restart Nginx with `sudo service nginx restart`