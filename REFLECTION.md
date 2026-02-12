The path that an HTTP request takes from your browser to the site is the following:
1. Your browser preforms a DNS lookup on the url that you inputed in order to convert it into an IP address.
2. After the IP address has been obtained, the browser sends the the HTTP request, which consists of the HTTP version, the HTTP method, the requested path, and any extra headers.
3. When the server recieves this request, it process it, and if necessary sends back a response.

Docker containeres are a much more powerful and versatile than Github pages. Github pages is primairly used to serve static webpages, whereas docker containers can run entire programs and applications within them. Github pages is most likely a stripped down version of a docker container, containing only the necessary stuff to host a webpage, such as a web server and a load balancer. 

AI Attribution: No AI was used in this Homework