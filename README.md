# Using locally trusted certificates for local development with Docker and Traefik  or Nginx
An easy way of having trusted self signed certs for local development needs.  
We’re assuming you work on a Mac OS machine and you use Docker.  
Tool used:  
 - mkcert 
 - dnsmasq

## mkcert
A simple zero-config tool to make locally trusted development certificates with any names you'd like  
https://github.com/FiloSottile/mkcert  
  
## dnsmasq
Wildcard DNS in localhost development  
https://gist.github.com/eloypnd/5efc3b590e7c738630fdcf0c10b68072  
  
## Nginx option
    cd nginx-https     
    make up  
open https://nginx-https-demo.localhost  
Read the specific [README](nginx-https/README.md)

## Traefik option
    cd traefik-https     
    make up   
open https://traefik-https-demo.localhost  
Read the specific [README](traefik-https/README.md)