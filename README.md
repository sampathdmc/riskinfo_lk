
Setting up the vagrant box
--------------
	git clone https://github.com/vdeparday/riskinfo_lk2.git

Change the ip in the VagrantFile to a valid ip on the local network 

	vagrant up
	vagrant ssh
The basic box will be downloaded automatically and will be provisioned with GeoNode (see the bash script)

	geonode createsuperuser