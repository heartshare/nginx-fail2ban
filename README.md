# nginx-fail2ban
This is my standard setup for protecting nginx with fail2ban and basic firewall rules. By utilizing nginx's request and connection limiting functionality and it's error logs you can configure fail2ban to issue iptables rules to limit the impact of DDoS Attacks targetting the nginx web server. It's not perfect however it heavily limits the impact of attacks.
