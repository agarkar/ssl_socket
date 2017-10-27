# ssl_socket
Simple ssl socket client-server program using self-signed certificates
Create Self-signed certificates
-------------------------------

the "gen_certs" script will create the self-signed server and client
certificates.

1. go to certs directory 

2. run ./gen_certs to create certificates.

3. copy the server certificates, key file and CA certificate to /etc/VX/CERTS
	/etc/CERTS/cacert.pem
	/etc/CERTS/server-crt.pem
	/etc/CERTS/server-key.pem

4. copy the client certificates, key file and CA certificate to /etc/VX/CERTS
	/etc/CERTS/cacert.pem
	/etc/CERTS/client-crt.pem
	/etc/CERTS/client-key.pem

Compiling Sample SSL socket programs
------------------------------------
1. run "make all" to compile SSL socket server and client program.

2. copy respective binaries on server/client and enjoy!!!!!!

