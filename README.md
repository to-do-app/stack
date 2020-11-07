# To-do app CloudFormation stack deployer

docker run -it --rm --name certbot -v "/etc/letsencrypt:/etc/letsencrypt" -v "/var/lib/letsencrypt:/var/lib/letsencrypt" -p 80:80 -p 443:443 certbot/certbot certonly --standalone --non-interactive --agree-tos --email alvarogarciafer@gmail.com --domains todoapp.duckdns.org
