## Are you running NGINX and want to add Brotli compression? 

With this script, that has been modified and updated to work with latest Brotli versions, you can make dynamic Brotli modules which upgrade whenever NGINX does.


To run mkbrotli in post-upgrade:

`nano /etc/apt/apt.conf.d/100-nginx-post-upgrade`

And paste in the following:

> DPkg::Post-Invoke {"/home/user/mkbrotli"; };
