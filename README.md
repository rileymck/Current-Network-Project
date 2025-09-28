https://rileymck07.com/

# To find out more about this project please read the "Network Project Documentation.docx"

# Original Idea: 
The original idea behind this project was to combine my knowledge of programming and security to make something public so employers can contact me. I wanted to make my own small network which would have consisted of a web server, firewall, a home lab, and an access point for all my smaller devices. This would have allowed me to make an internal network zone and a DMZ (Demilitarized Zone). However while doing this project I ran into problems, mostly with the firewall, which made me completely redesign how this project was going to work. 


# Attempt 4 (Firewall: UFW and Cloudflare; Web Server: Nginx):
What am I currently running on my web server?
- Nginx: Serves as a high performance web server, acts as a reverse proxy, load balancer, and cache to efficiently handle and distribute web traffic for my website
- UFW Firewall: Simplifies the management of iptabless firewall rules on linux systems
- SSH: Provides a secure way to access and manage remote computers over an unsecured network
- Cloudflare: Makes websites and applications faster, more secure, and highly available by acting as a content delivery network (CDN), DDoS mitigation service, and reverse proxy
- Others which include: Cron(allows users to automate repetitive tasks by scheduling them to run at specific times or intervals), bluetooth, rsyslog (logging), and avahi-daemon(performs zero configuration networking allowing devices on a local network to automatically discover and communicate with each other without manual configuration


# Future improvements:
- Download OpenWRT OS on my Raspberry Pi for firewall software
- Get a managed switch for VLAN, port monitoring, and QoS support
- Do more research to see if my ISP has ports 443, 80, and 22 open

By doing these few things I believe I can make a working firewall and direct the traffic myself instead of having someone else do it for me. If I'm able to get a firewall working then ill need to wire it all up and make another SSH key pair gen, but that's a given. 


# Quick shout out:
Thank you to Josh Gorden for helping me with some problems I ran into along the way. If you go and look at the "Network Project Documentation.docx" you can find his website and his LinkedIn profile.
