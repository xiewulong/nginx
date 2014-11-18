nginx
=====

#create CA
#openssl genrsa -des3 -out cert.key 1024
#openssl req -new -key cert.key -out cert.csr
#openssl rsa -in cert.key -out cert_nopwd.key
#openssl x509 -req -days 365 -in cert.csr -signkey cert_nopwd.key -out cert.crt