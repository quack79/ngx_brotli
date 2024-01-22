# Can be run in post-upgrade by creating "/etc/apt/apt.conf.d/100-nginx-post-update"
> DPkg::Post-Invoke {"/home/user/mkbrotli"; };

# Modified and updated to work with newest Brotli versions, and only runs if NGINX has been updated
