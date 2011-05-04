Why?
====================
I didn't like the current offerings available.

Configuration
====================
Feel to fork this and change the top variables with your configuration.

	nano /etc/init.d/nginx
	chmod +x /etc/init.d/nginx
	update-rc.d nginx defaults

Notes
====================
This is a modified nginx init `apt-get` script. 
It should work with a vanilla (defaults) build of nginx.

Example
====================
	/etc/init.d/nginx start
	/etc/init.d/nginx stop
	/etc/init.d/nginx status