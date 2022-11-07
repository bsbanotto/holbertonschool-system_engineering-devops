This is a README file for project 0x02. Load balancer

There are two mandatory tasks in this project as follows:

Task 0 - Double the number of webservers
 - Add a custom Nginx response header to track which web server is
   answering HTTP requests.
    - The name of the custom HTTP header must be X-Served-By
    - The value of the custom HTTMP headermust be the hostname of the 
      server Nginx is runnig on
 - Write 0-custom_http_response_header BASH script so that it configures
   a brand new Ubuntu machine to the requirements of this task

Task 1 - Install and configure HAprox on lb-01 server
 - Configure HAproxy so that is sends traffic to web-01 and web-02
 - Distribute requests using a roundrobin algorithm (default)
 - Make sure that HAproxy can be managed via an init script
 - Make sure that my servers are configured using the right host name
 - Answer file is a BASH script that configures this new Ubuntu machine
   to respect all of these requirements.
