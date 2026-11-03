# ADT_DevOps_7_HTTPS
Simple EC2 server, but this time with HTTPS - via a self-signed certificate.



* Note:  This creates a self-signed certificate, which ensures that traffic is encrypted.
*
* However, without a separate domain and certificate signed by a CA, the browser cannot guarantee the site is legitimate and will mark it as 'insecure'.
* BPP's filtering will BLOCK the site also!
