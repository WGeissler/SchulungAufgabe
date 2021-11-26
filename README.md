# SchulungAufgabe

## How to install this image 

`docker pull quay.io/wgeissler/bechtle-web-image`

###### Find out your IP address 

> docker inspect bechlte-web 

Its written down under "Networks" and "IPAddress" 
 

###### Expose your Ports 

> docker run --name bechtle-web -d -p 8080:80 bechtle-web-image 


###### Open the Webserver 

 
You can open the Webserver in the CLI:

> curl localhost:8080

Or you can open the Webserver in your brwoser by typing in the IP Address.
