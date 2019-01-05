Connect
	ssh 23.238.155.107 -p 2200
	http://23.238.155.107

Instalation and configurations
	finger installed
	added sudo user billy
	added sudo user grader password = udacity
	ssh port switched to 2200
	extended time out settings on ssh 
	added public ssh keys
	disabled root ssh login
	disabled password login

	installed apache2
	installed python-pip virtualenv
	installed libapache2-mod-wsgi -y
	installed python3-pip
	created flask folder in /var/www
	created Catalog folder in /var/www/flask
	cloned https://github.com/RedWhistleProductions/Catalog.git into /var/www/flask/Catalog
	created flask.wsgi
	ran SetUp.sh
	installed postgresql and setup users and permisions
	ran SetUpDb.py
	ran Populate.py

	created and enabled flask.conf to /etc/apache2/sites_available
	disabled 000-default.conf