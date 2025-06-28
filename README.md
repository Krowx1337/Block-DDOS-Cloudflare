# Cloudflare Rules
Rules of Cloudflare Firewall for Block Bad Bot and Exploiting. Made by [Krowx](https://krowx.xyz/)

* Important: *If you have any problems or questions, please contact Cloudflare support. These rules are general for review and it happens that they do not work stably on all sites, so you have to edit them yourself for your sites. They do not guarantee you complete protection, but only help to cope with common attacks.*

![Cloudflare Banner](https://imgs.search.brave.com/vMssRmSQL8CxVIYYu6fluUEdgYemos7Kx5djNyAncas/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9ib290/ZmxhcmUuY29tL3dw/LWNvbnRlbnQvdXBs/b2Fkcy8yMDIzLzAz/L0Nsb3VkZmxhcmUt/TG9nby5wbmc)

# 1. Bad Bot - Action Block [(open)](Bad%20Bot%20-%20Block.txt)
> * Blocks popular bad User Agent
> * Blocks connections by port (usually only bots do this)
> * Blocks outdated versions HTTP (1.0)
> * Blocks bad threats flagged by cloudflare
> * Blocks bad method requests
> * Blocks suspicious X-Forwarded-For
> * Blocks requests from the Tor network
> * Blocks ASN list of most known proxy scraping sites
> * Blocks non-standard cookies

# 2. Exploiting Fix - Action Block [(open)](Exploiting%20Fix%20-%20Block.txt)
> * Blocking queries with SQL vulnerabilities
> * Blocking queries with XSS vulnerabilities
> * Block popular PHP vulnerabilities
> 
> ...

# 3. Method Fix (Optional) - Action Block [(open)](Method%20Fix%20-%20Block.txt)
> * Blocks unusual attack methods that we have detected

# 4. Threat Check (Optional) - Action Challenge [(open)](Threat%20Check%20-%20Challenge.txt)
> * Checking for outdated versions HTTP (1.1, 1.2)
> * Checking countries that allow a lot of malicious traffic
> * Checking bad threats flagged by cloudflare
> * Checking for insecure requests (Not SSL requests)
> * Checking requests of unknown origin (Not have referer)

# How to use?
*Copy the expression and paste it into your expression builder*
![image](https://user-images.githubusercontent.com/55624740/161973398-05e74f0c-f72c-4c71-afa4-46987801f3c8.png)

# Would you like to support me?
* Join on my Discord - [![Discord](https://img.shields.io/badge/Discord-000000?style=for-the-badge&logo=discord&logoColor=6A0DAD)](https://discord.gg/crimelifecl/) 

# Need any help? - Contact me!
* Here you go --> [![Discord](https://img.shields.io/badge/Discord-000000?style=for-the-badge&logo=discord&logoColor=6A0DAD)](https://discord.com/users/1103038390481465434)  
