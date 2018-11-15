# SmartDNS-Proxy-Server
DNSMasq + SNIProxy = SmartDNS Proxy

## Issue
This Proxy Server is for UK TV Channel Sites.
If you use this Proxy, you can watch UK TV Channels in everywhere in the world.

*What is Issue???*
```
If you input the URL as http://www.bbc.co.uk, since you are first not registered to our site, you will be redirected to our landing page.
https://www.channelhopper.tv/register.php?From_URL=http://www.bbc.co.uk

But if you input https instead of http, you can see the security warning.
This is very serious unsolvable issue.
We support over 100 channel domains and whichever you select, all goes to the landing page.
The problem is in here.
Our ssl cert has only one domain but all channel domains try to connect ssl with our cert.

Is there any solution to avoid security error without changing the cert???
```
