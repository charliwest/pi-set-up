# pi-set-up
How I set up my pi's including external access

Commands to set up htpasswd for nginx

On the pi running nginx
     sudo apt-get install apache2-utils
     sudo htpasswd -c /etc/nginx/.htpasswd exampleuser

Change exampleuser to the user you want to log in as 
The tool will prompt you for a password.
    New password:
    Re-type new password:
    Adding password for user exampleuser
