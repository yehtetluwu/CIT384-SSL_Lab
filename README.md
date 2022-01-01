# CIT384-SSL_Lab

# We had to create a dockerfile that will use self-signed certificates with [OpenSSL](https://www.openssl.org/) and do the followings.

1. Create vHost files for `site1.internal`, `site2.internal`, `site3.internal`. 
1. Turn on [SSLEngine](https://httpd.apache.org/docs/2.4/mod/mod_ssl.html) and add [RewriteRule](https://httpd.apache.org/docs/2.4/mod/mod_rewrite.html) to force `https://site1.internal` as well as a new Block for 443 traffic.
1. Create an HTML file for serving.
1. Install Apache2 and other necessary modules
1. Enable necessary modules
1. Create self-signed certificates    
