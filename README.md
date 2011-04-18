nginx init.d script to start/stop/status etc (modified one from Debian 6 nignx repo for compiled nginx)

Modifted nginx init `apt-get` script should work with a vanilla (defaults) copy of nginx when compiled 

Stuff to do when setting up this script:

	nano /etc/init.d/nginx
	chmod +x /etc/init.d/nginx
	update-rc.d nginx defaults
	
Test it

	/etc/init.d/nginx start
	/etc/init.d/nginx stop
	/etc/init.d/nginx status